---
title: Network Error Pages
template: index.jade
---

These are error pages which complement the visual style established in
[Project Chameleon](http://people.mozilla.org/~jgruen/chameleon/).

Best viewed in a recent version of Firefox. Things break in other browsers.

## Specifications

### Server not found

#### Old Copy

<iframe src="prototypes/server-not-found.html" class="netErrorProto"></iframe>

#### New copy

Note: The search engine is based off of the user's selected search engine. Do
not interpret this as Firefox changing its default search engine.

<iframe src="prototypes/page-not-found.html" class="netErrorProto" style="height: 300px"></iframe>

### Connection Issues

Miscellaneous connection errors have been grouped together. This includes:

* Connection Timeout
* Connection Reset
* Connection Interrupted
* Connection Failure
* Unknown Socket

If the user keeps getting the same error, they will get some extra copy. Try
pressing the "try again" button a few times yourself.

<iframe src="prototypes/connection-issue.html" class="netErrorProto" style="height: 360px"></iframe>

In case the copy is too edgy, a watered down version is available too.

> It looks like the site Firefox keeps trying to reach is not working
at this time. You way want to try the site again at a later time.

Icon authored by [Dmitri Kunin](http://thenounproject.com/dmitri.kunin/) and
released into the Public Domain.

### No internet connection

A new error page should be created which will be triggered when a network error
happens as a result of the user not being connected to the internet. More discussion and rationale can be found in [Internet Connectivity discussion](https://people.mozilla.org/~vtsatskin/notes/Projects/Message%20Cleanup/proposed.design).

If the operating system has a network diagnostics tool such as OS X and Windows,
the following error page will be shown.

<iframe src="prototypes/no-internet.html" class="netErrorProto" style="height: 280px"></iframe>

Otherwise, if the steps are known how to diagnose the internet connection,
display system specific instructions as follows.

<iframe src="prototypes/no-internet-instructions.html" class="netErrorProto" style="height: 280px"></iframe>

If no information is known how to solve the problem (e.g esoteric distribution of BSD), something like the following copy can be used.

> Go to your computer's network settings to ensure your internet connection is
configured correctly.

Once the network error has been resolved and Firefox detects a working
connection, the user's tab should be **automatically reloaded** to display the
page.

A WiFi icon was chosen due to ever-growing popularity of wireless connections.
The assumption is that most people should be able to understand the wifi symbol.

The icon is authored by [Ugur Akdemir](thenounproject.com/ugur.akdemir/) and
licensed under Creative Commons – Attribution (CC BY 3.0).

### Page display error

#### Content Encoding

<iframe src="prototypes/content-encoding.html" class="netErrorProto" style="height: 340px"></iframe>

#### Corrupted Content

<iframe src="prototypes/corrupted-content.html" class="netErrorProto" style="height: 340px"></iframe>

### Removed Errors

"Invalid Address" and "Malformed URI" should both be treated as search results.

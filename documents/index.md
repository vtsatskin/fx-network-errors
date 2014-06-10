---
title: Network Error Pages
template: index.jade
---

These are error pages which complement the visual style established in
[Project Chameleon](http://people.mozilla.org/~jgruen/chameleon/).

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

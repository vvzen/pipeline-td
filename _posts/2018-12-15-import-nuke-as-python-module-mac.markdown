---
layout: post
title:  "Import Nuke as python module (macOS)"
date:   2018-12-16 16:01:46 +0100
categories: jekyll update
---

In case you've been wondering if it's possible to use nuke's API outside of Nuke, you're not alone.
It's a very common and pratical thing to do.

*If you're on linux or windows.*

If you're on macOS, it's not as straightforward.

Straight from The Foundry support:

<em>Hey Valerio,
<br/>
<br/>
Thank you for confirming that you see the same thing using the `/usr/bin/python` version. (note: a segmentation fault while importing nuke.so from python)
<br/>
<br/>
I have been talking with the developers about this, and unfortunately, <strong>setting up the correct libraries for the Nuke module to be imported into an external Python is more complex than just importing the nuke.so file</strong>. This is due to how applications needs to be packed in specific ways to work with Mac, which is why it works correctly on Linux and Windows.
<br/>
<br/>
The simplest way to get a working version would be to use the Python version that ships with Nuke, to run the scripts that you need.
<br/>
<br/>
This Python version can be found here: `/Applications/Nuke11.2v3/Nuke11.2v3.app/Contents/MacOS/python.app`
<br/>
<br/>
It is theoretically possible to set up an external Python version in the same way, however we strongly recommend using the one that ships inside Nuke, as we don't test using external versions of Python.
<br/>
<br/>
I hope this information helps.
<br/>
<br/>
Kind Regards,
<br/>
<br/>
Peter
</em>
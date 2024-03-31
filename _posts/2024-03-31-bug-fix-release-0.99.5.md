---
layout: post
title: Shutter 0.99.5 - more bug fixes
author: Michael Kogan
permalink: /releases/0.99.5/
tags: [release]
---

After another long period of time with no new releases, the Shutter team is happy to announce a new, mostly bug fix, release 0.99.5. 

Bug fixes:

* Fixed loading and saving profiles
* Fixed the editor being unavailable under some circumstances
* Fixed crash when selection has zero width or height
* Check to prevent user setting a filename pattern without wildcards, which lead to crashes
* Fixed crash on Wayland under some circumstances
* Fixed crash when the autostart .desktop file is not writable
* Fixed handling images pasted from clipboard: they are now handled the same as screenshots made by Shutter itself, rather than being put into /tmp
* Fixed error when using the -s option with a zero coordinate for the selection origin

New features:

* Added WebP support
* In Selection mode added an option to take screenshot on releasing the mouse button without confirmation

New optional dependency for WebP support: [webp-pixbuf-loader](https://github.com/aruiz/webp-pixbuf-loader)

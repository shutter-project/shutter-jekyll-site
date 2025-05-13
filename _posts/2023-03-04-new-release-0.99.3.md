---
layout: release
title: Shutter 0.99.3 - some more bug fixes for 2023
author: Alexey Sokolov
permalink: /releases/0.99.3/
version: 0.99.3
tags: [release]
---

After a long time there is another bugfix release:

* Improved code quality a bit, added a few unit tests (thanks to Alexander Ruzhnikov!)
* Fixed font size in the editor
* Fixed loading of profiles
* Fixed crash when taking too small screenshots
* Fixed appearance of the web capture button
* Fixed XML schema of AppData
* Allow more valid character in filenames
* Removed dysfunctional upload plugins
* Added a visible warning about limited functionality on Wayland

New dependency: [Moo](https://metacpan.org/pod/Moo)

Dropped dependencies: libwww-mechanize-perl, libwww-perl, libnet-oauth-perl

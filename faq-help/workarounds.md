---
layout: page
---
### Workarounds

Here we collect workarounds for issues which arise due to problems with other projects ("not our bugs").

#### Crashes and limited functionality for DWM users

DWM doesn't support _NET_CLIENT_LIST and ewmh by default. Because of that Shutter crashes on startup and cannot access open windows in Window Capture mode. Please use the following two DWM patches to make Shutter work with DWM:

For implementing _NET_CLIENT_LIST support and getting rid of the crash on startup please use [this patch](https://github.com/bakkeby/patches/blob/master/dwm/dwm-netclientliststacking-6.2.diff).

For implementing emwh support and detecting windows correctly in Window Capture mode please use [this patch](https://dwm.suckless.org/patches/ewmhtags/).

#### Second instance crash (for versions up to 0.95)

Old Shutter versions used Gtk2-Unique which is subject to a bug leading to a crash in Shutter when one instance is running and another one is started. apply the following patches to your Gtk2-Unique library: [Patch 1](https://aur.archlinux.org/cgit/aur.git/tree/fix_segfault_2nd_instance.patch?h=perl-gtk2-unique&id=df98d4f2635910b86733892c1798f317ba52c26d) and [Patch 2](https://aur.archlinux.org/cgit/aur.git/tree/perl-gtk2-unique.patch?h=perl-gtk2-unique&id=df98d4f2635910b86733892c1798f317ba52c26d).

#### Further workaround necessary?

Please [contact us](https://shutter-project.org/contact/) if you ran into a problem which cannot be fixed in Shutter itself but know a workaround!

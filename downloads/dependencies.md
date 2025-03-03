---
layout: page
---
### Dependencies

Note: If you are interested in the latest git snapshot or you want to use the tar.gz archives to get Shutter running on your system, please make sure you meet the dependencies (the name of the packages may differ):

#### Mandatory:

  * Since 0.99.3:
    * [Moo](https://metacpan.org/pod/Moo)
  * Since 0.96:
    * [Carp:::Always](https://metacpan.org/pod/Carp::Always)
    * [Gtk3](https://metacpan.org/pod/Gtk3)
    * [Gtk3::ImageView](https://metacpan.org/pod/Gtk3::ImageView) >= 10
    * [GooCanvas2](https://metacpan.org/pod/GooCanvas2)
    * [GooCanvas2::CairoTypes](https://metacpan.org/pod/GooCanvas2::CairoTypes)
    * [Pango](https://metacpan.org/pod/Pango)
    * [libwnck-3](https://gitlab.gnome.org/GNOME/libwnck), used via Glib Object Introspection
  * Since before that:
    * libglib-perl
    * liblocale-gettext-perl
    * libxml-simple-perl
    * libnet-dbus-perl
    * imagemagick
    * perlmagick
    * libx11-protocol-perl
    * librsvg2-common
    * xdg-utils
    * procps
    * librsvg
    * libproc-processtable-perl (since 0.86.2)
    * libpath-class-perl (since 0.88)
    * libjson-perl (since 0.88)
    * libjson-maybexs-perl (since 0.94.1)
    * libfile-which-perl (since 0.88)
    * libfile-spec-perl (since 0.88)
    * libfile-basedir-perl (since 0.88)
    * libfile-copy-recursive-perl (since 0.88)
    * libproc-simple-perl (since 0.88)
    * libsort-naturally-perl (since 0.88)
    * libnumber-bytes-human-perl (since 0.95)
    * libglib-object-introspection-perl (since 0.95)

#### Optional:
  * libavif and possibly libavif-gdk-pixbuf (since 0.99.6) for AVIF support
  * webp-pixbuf-loader (since 0.99.5) for WebP support
  * xdg-desktop-portal (since 0.99.1) for Wayland support
    * You will also need one of its backends installed, such as xdg-desktop-portal-kde, xdg-desktop-portal-gtk, xdg-desktop-portal-wlr, etc. The backend needs to match the wayland compositor you're using.
  * Either gir1.2-appindicator3 (since 0.96) or gir1.2-ayatanaappindicator3 (supported since 0.99)
    If neither is installed, the tray icon will be missing on Gnome
  * libimage-exiftool-perl (since 0.87)
  Enables Shutter to write Metadata (Orientation) when saving Jpeg-Files instead of simply rotating the image
  * gnome-web-photo
  Shutter uses gnome-web-photo to capture websites
  * nautilus-sendto
  Enables the “Send To…”-functionality in right-click menu and main menu (“Screenshot”)

#### Not needed any more:

  * libgnome2-perl (no longer needed in versions >= 0.95)
  * libgnome2-vfs-perl (no longer needed in versions >= 0.95)
  * libgnome2-gconf-perl (no longer needed in versions >= 0.90)
  * libgtk2-trayicon-perl (only if you are using a gtk2 version lower than 2.10.x)
  * libjson-xs-perl (no longer needed in versions >= 0.94.1)
  * libnet-dropbox-api-perl (no longer needed in versions >= 0.92)
  * libnet-dbus-glib-perl (no longer needed since Ubuntu One has been closed)
  * libgtk2-perl (no longer needed in versions >= 0.96)
  * libgtk2-imageview-perl (no longer needed in versions >= 0.96)
  * libgnome2-wnck-perl (no longer needed in versions >= 0.96)
  * libgoo-canvas-perl (no longer needed in versions >= 0.96)
  * libgtk2-appindicator-perl (no longer needed in versions >= 0.96)
  * libgtk2-unique-perl (no longer needed in versions >= 0.96)
  * libwww-mechanize-perl (no longer needed in versions >= 0.99.3)
  * libwww-perl (no longer needed in versions >= 0.99.3)
  * libnet-oauth-perl (no longer needed in versions >= 0.99.3)

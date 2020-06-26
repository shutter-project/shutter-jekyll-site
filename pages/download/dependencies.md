### Dependencies

Note: If you are interested in the latest git snapshot or you want to use the tar.gz archives to get Shutter running on your system, please make sure you meet the dependencies (the name of the packages may differ):

#### Mandatory:

  * libgtk2-perl
  * libgtk2-imageview-perl
  * libglib-perl
  * libgnome2-wnck-perl
  * liblocale-gettext-perl
  * libxml-simple-perl
  * libwww-mechanize-perl
  * libwww-perl
  * libnet-dbus-perl
  * imagemagick
  * perlmagick
  * libx11-protocol-perl
  * librsvg2-common
  * xdg-utils
  * procps
  * librsvg
  * libproc-processtable-perl (since 0.86.2)
  * libgtk2-unique-perl (since 0.87)
  * libpath-class-perl (since 0.88)
  * libjson-perl (since 0.88)
  * libjson-maybexs-perl (since 0.94.1)
  * libfile-which-perl (since 0.88)
  * libfile-spec-perl (since 0.88)
  * libfile-basedir-perl (since 0.88)
  * libfile-copy-recursive-perl (since 0.88)
  * libproc-simple-perl (since 0.88)
  * libsort-naturally-perl (since 0.88)
  * libnumber-bytes-human-perl (NEW! since 0.95)
  * libglib-object-introspection-perl (NEW! since 0.95)

#### Optional:

  * libgtk2-appindicator-perl (since 0.89)  
  Adds support for Application Indicators
  * libimage-exiftool-perl (since 0.87)  
  Enables Shutter to write Metadata (Orientation) when saving Jpeg-Files instead of simply rotating the image
  * gnome-web-photo  
  Shutter uses gnome-web-photo to capture websites
  * libgoo-canvas-perl  
  Allows you to edit the screenshots directly using a built-in editor
  * nautilus-sendto  
  Enables the “Send To…”-functionality in right-click menu and main menu (“Screenshot”)
  * libnet-oauth-perl (since 0.93)  
  Enables images upload to upload hosters using OAuth

#### Not needed any more:

  * libgnome2-perl (no longer needed in versions >= 0.95)
  * libgnome2-vfs-perl (no longer needed in versions >= 0.95)
  * libgnome2-gconf-perl (no longer needed in versions >= 0.90)
  * libgtk2-trayicon-perl (only if you are using a gtk2 version lower than 2.10.x)
  * libjson-xs-perl (no longer needed in versions >= 0.94.1)
  * libnet-dropbox-api-perl (no longer needed in versions >= 0.92)
  * libnet-dbus-glib-perl (no longer needed since Ubuntu One has been closed)

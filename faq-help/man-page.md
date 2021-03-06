---
layout: page
---
~~~
SHUTTER(1)                                                     User Contributed Perl Documentation                                                     SHUTTER(1)

NAME
       Shutter - Feature-rich Screenshot Tool

SYNOPSIS
       shutter [options]

COPYRIGHT
       Shutter is Copyright (C) by Mario Kemper and Shutter Team

DESCRIPTION
       Shutter is a feature-rich screenshot program. You can take a screenshot of a specific area, window, your whole screen, or even of a website - apply
       different effects to it, draw on it to highlight points, and then upload to an image hosting site, all within one window.

OPTIONS
       Example 1
               shutter -a -p=myprofile --min_at_startup

       Example 2
               shutter -s=100,100,300,300 -e

       Example 3
               shutter --window=.*firefox.*

       Example 4
               shutter --web=http://shutter-project.org/ -e

   CAPTURE MODE OPTIONS
       -s, --select=[X,Y,WIDTH,HEIGHT]
               Capture an area of the screen. Providing X,Y,WIDTH,HEIGHT is optional.

       -f, --full
               Capture the entire screen.

       -w, --window=[NAME_PATTERN]
               Select a window to capture. Providing a NAME_PATTERN (Perl-style regex) ist optional.

       -a, --active
               Capture the current active window.

       --section
               Capture a section. You will be able to select any child window by moving the mouse over it.

       -m, --menu
               Capture a menu.

       -t, --tooltip
               Capture a tooltip.

       --web=[URL]
               Capture a webpage. Providing an URL ist optional.

       -r, --redo
               Redo last screenshot.

   SETTINGS OPTIONS
       -p, --profile=NAME
               Load a specific profile on startup.

       -o, --output=FILENAME
               Specify a filename to save the screenshot to (overwrites any profile-related setting).

               Supported image formats: You can save to any popular image format (e.g. jpeg, png, gif, bmp). Additionally it is possible to save to pdf, ps or
               svg.

               Please note: There are several wildcards available, like

                %Y = year
                %m = month
                %d = day
                %T = time
                $w = width
                $h = height
                $name = multi-purpose (e.g. window title)
                $nb_name = like $name but without blanks in resulting strings
                $profile = name of current profile
                $R = random char (e.g. $RRRR = ag4r)
                %NN = counter

               The string is interpretted by strftime. See "man strftime" for more examples.

               As an example: shutter -f -e -o './%y-%m-%d_$w_$h.png' would create a file named '11-10-28_1280_800.png' in the current directory.

       -d, --delay=SECONDS
               Wait n seconds before taking a screenshot.

       -c, --include_cursor
               Include cursor when taking a screenshot.

       -C, --remove_cursor
               Remove cursor when taking a screenshot.

   APPLICATION OPTIONS
       -h, --help
               Prints a brief help message and exits.

       -v, --version
               Prints version information.

       --debug Prints a lot of debugging information to STDOUT.

       --clear_cache
               Clears cache, e.g. installed plugins, at startup.

       --min_at_startup
               Starts Shutter minimized to tray.

       --disable_systray
               Disables systray icon.

       -e, --exit_after_capture
               Exit after the first capture has been made. This is useful when using Shutter in scripts.

       -n, --no_session
               Do not add the screenshot to the session. This is useful when using Shutter in scripts.

BUG REPORTS
       If you find a bug in Shutter, you should report it.  But first, you should make sure that it really is a bug, and that it appears in the latest version of
       Shutter.

       The latest version is always available from: https://github.com/shutter-project/shutter/releases

       Once you have determined that a bug actually exists, please report it at github: https://github.com/shutter-project/shutter/issues/new

perl v5.32.0                                                                2020-06-21                                                                 SHUTTER(1)
~~~

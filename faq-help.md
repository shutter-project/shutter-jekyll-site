---
layout: page
---
### FAQ & Help

1. **I want Shutter to be the default tool to take screenshots with. How do I do that?**
  Shutter provides a built-in functionality to setup the global shortcuts if you are using GNOME. A detailed description and solutions for other desktop environments are available [here](set-shutter-as-the-default-screenshot-tool).
2. **I want to open my screenshot in an external application but the ‘Open with’ menu entry is empty. Why are my installed apps not listed here?**
  You don’t seem to have any mimeinfo.cache files. Try running the update-desktop-database command. If you  don’t have this command you should install the desktop-file-utils package.
3. **Are there any plans to develop Shutter for Window, Mac OS or any other platform that is not GNU/Linux (or related)?**
  I totally agree that supporting as many platforms as possible should be a target for most software projects nowadays, but there are some good – in my opinion – reasons against this in some special cases.  
  One of the most important things is that Shutter depends on software components that are only available on Linux and comparable platforms (e.g. some gnome libraries and especially a fully working X-Server). Shutter is using xlib calls in many cases to perform the various tasks of taking screenshots. Most parts of the application had to be rewritten when multi-platform would be a future goal. Currently this project is a two men project and it is just impossible to “implement new features and improving the app” AND “spending months in writing several backends to support more platforms”.  
  Another reason that comes to my mind is that there are already a lot screenshot taking applications for windows (freeware and professional software). I am unsure if the huge amount of work would be worth it. The fact that there was no dedicated screenshot application for Linux was one of the main reasons for starting Shutter and I am still convinced that it is useful for a lot of people who need some more features than offered by standard tools.  
Nevertheless, this is an open-source project and anyone could start a port of Shutter at any time…to any platforms possible. I am always willing to assist where I can.
4. **Are there any plans to add Wayland support in Shutter?**
   Shutter is mostly in maintanence mode since its original developer's withdrawal and the GTK3 port several years later. The current dev team gives its best to keep Shutter afloat and fix the most pressing issues. However, Wayland support is a very big task and there are several technical difficulties that need to be overcome. Though we understand that this is a major issue for Wayland users, we are currently unable to solve the technical problems and add full Wayland support to Shutter. For the moment Shutter supports only the capture via XDG Portal in Wayland (most commonly, it is fullscreen, but depends on the portal). Additional features like the editor, image uploading, plugins etc. are available as well. You can find the discussion regarding Wayland support [here](https://github.com/shutter-project/shutter/issues/187).

If you have further questions, please [contact us](../contact)!

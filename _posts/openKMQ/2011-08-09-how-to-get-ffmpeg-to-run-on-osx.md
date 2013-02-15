---
layout : post
category : content
tags : [ffmpeg, open source, OSX, trueColor3D]
---
{% include JB/setup %}

ffmpeg is a so called command line tool for audio/video file conversion and processing.

It's an open source project and parts of (depending on its configuration) it are not allowed to be redistributed in binary form without also providing the full source code.

For now, I suggest you take the time to download some free tools and source codes and to start the so called build process on your Mac on your own.

To build ffmpeg configured with all the parts needed to serve as trueColor3D's processing engine, 
you need 

* XCode from the Apple MacAppStore

* The [MacPorts project](http://www.macports.org/)

* FFMpeg from it's source code repository

You may need to launch the Terminal.app and type in and launch some commands.

+ Install XCode (should be free for Lion and just $3.99 for SnowLeopard). 
  And also install its command line tools.

+ Download the port command from the [MacPort project](http://www.macports.org) 
  and follow the instruction to build it with the gcc compiler that came with XCode command line tools.

+ type in "sudo port install ffmpeg" and enter your admin/root password to download 
  and build and install the ffmpeg program.

---
layout : post
category : content
tags : [GRilli3D, ipad3D, KMQ, Lorgnette, My3D, openKMQ, openKQM3D, openMy3D, stereoscopic, Stereoskopie, vimeo, vimeo3D, YouTube3D, YT3D]
---
{% include JB/setup %}

First trueColor3D only ran on Windows, because it strongly depended on the AviSynth audio/video 
scripting environment that is tricky to run on non-Windows machines.

I started to reprogram many of the conversions from AviSynth to only use video filter commands 
in ffmpeg.

This is the first result.

On OSX, the following old/new stereo-layouts are supported :

	Youtube: my3D, iPad (over/under 1080p)
	Vimeo: my3D, iPad (over/under), PC (over/under)
	home use: my3D, iPad (iTunes), iPad (AirVideo)

Download version 0.95 from my DropBox : 

  [Source code only (v0.95)](http://dl.dropbox.com/u/7623044/openKMQ/trueColor3D_0_95_src.zip), 

  [Windows 32-bit binary (v0.94)](http://dl.dropbox.com/u/7623044/openKMQ/trueColor3D_0_94_win.zip),

  [OSX 32-bit binary (v0.95)](http://dl.dropbox.com/u/7623044/openKMQ/trueColor3D_0_95_OSX_bin.zip)
---
layout: post
title: NME 3.1 RC4 Release
date: 2011-12-08 02:37:53.000000000 -08:00
---
We have a new version of NME ready to install. You can download the automated installer from the <a href="http://www.haxenme.org/developers/get-started" target="_blank">Get Started</a> page, or follow the instructions for <a href="http://www.haxenme.org/developers/get-started/manual-install" target="_blank">installing manually</a>.

NME 3.1 RC4 includes numerous small fixes for using the accelerometer on Android, embedding fonts on iOS, accessing text assets on HTML5, using Matrix3D and graphics.drawTriangles, as well as other useful improvements.

The big new feature in this release is improved extension support. You can now include custom Java classes in your project, and extensions have gotten a lot smarter -- you can now define multiple NDLL assets, classpaths, and even add your own defines or assets, just as you can from a regular project file. We'll be posting more about the improved format soon.

Also in this release is a tool to automatically create Haxe extern classes to instantiate and use your Java code, just as simply as you access your own classes. Instead of creating your own JNI bindings to talk to Java, you can have it all created for you. This tool is currently in beta, and we will be writing more about it shortly as well.

Thanks again for your continued support!

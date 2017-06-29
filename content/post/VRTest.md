+++
date = "2017-06-24T12:00:00-04:00"
description = "App to demonstrate my ability with the Android NDK"
draft = false
tags = ["Apps", "Android", "Java", "NDK", "JNI", "OpenGL"]
title = "VR Test"
topics = ["DriveSafe.ly"]

+++

## Screenshots

{{< gallery caption-effect="fade" >}}
  {{< figure thumb="-thumb" link="/img/app/vr-test/1.png" alt="Screenshot of the app">}}
{{< /gallery >}}

## Goal

The goal of this app is as a demonstration of my ability to write android native code that interfaces with OpenGL

## Completed tasks

Here's the list of what I completed:

 - The app relies on the module vr_mod_1.
 - The app uses RelativeLayout and several other UI elements to implement a YouTube like UI.
 - The UI adjusts itself for both screen size and orientation.
 - The app uses the JNI to implement C++ code, which is kept in the module vr_mod_1.

Bonus:

 - In the init() function of GLView of vr_mod_1, the native functions stringFromJNI() and jniCallback(Runnable) are used
 - The function stringFromJNI() relies on vr_mod_2 to call vr_mod_2::hello_mod_2().
 - The jniCallback native function runs a Runnable object taken as a parameter from Java.
 - The native functions init() and resize(int width, int height) use OpenGL to render a triangle natively.
 - The module vr_mod_1 uses Gradle split builds to build different apk's per ABI.

## My contribution
I wrote this app.

[Source Code](https://github.com/cyberpirate/VR-Test-App)
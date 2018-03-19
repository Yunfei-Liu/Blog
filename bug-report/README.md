# Bug report in using Ubuntu 16.04

## Error running ROS Mono
> **描述**:
> Terminal output:
``` bash
ORB-SLAM2 Copyright (C) 2014-2016 Raul Mur-Artal, University of Zaragoza.
This program comes with ABSOLUTELY NO WARRANTY;
This is free software, and you are welcome to redistribute it
under certain conditions. See LICENSE.txt.
Input sensor was set to: Monocular
Loading ORB Vocabulary. This could take a while...
Vocabulary loaded!
Camera Parameters:
fx: 535.4
fy: 539.2
cx: 320.1
cy: 247.6
k1: 0
k2: 0
p1: 0
p2: 0
fps: 30
color order: RGB (ignored if grayscale)
ORB Extractor Parameters:
Number of Features: 100
Scale Levels: 8
Scale Factor: 1.2
Initial Fast Threshold: 20
Minimum Fast Threshold: 7
(Mono:9555): Gtk-ERROR **: GTK+ 2.x symbols detected. Using GTK+ 2.x and GTK+ 3 in the same process is not supported
Trace/breakpoint trap (core dumped)
```

**问题原因**: 编译OpenCV的姿势不对

**解决方法**:
uninstall opencv then remake with cmake with your favorite flags and add `-D WITH_GTK_2_X=ON`
make sure to install necessary libraries `sudo apt install libgtk2.0-dev pkg-config`
and then rebuild ROS and reinstall ORB SLAM
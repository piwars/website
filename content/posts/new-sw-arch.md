---
title: New software architecture is on the way
date: 20181125T16:00:00+01:00
---

I've finally managed to do a major update of the software of the robot. Hopefully this new architecture will make it easier to develop and debug.

<!--more-->

# Go and C

I'm still using Go as the main programming language, with some call to the C language for libraries such as [wiringPI](http://wiringpi.com/) and [libav](https://libav.org/). The main difference now is that instead of having an intermediate HAL library (Hardware Abstraction Layer) which contained all the low level C library dedicated to the control of the robot, I am now doing this in go directly.


# Why Go?


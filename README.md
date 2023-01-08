# NanoPi R5S Ubuntu minimal image

This is the Ubuntu minimal image with kernel 5.10.110 with CLI (Command Line Interface, no Desktop) for development purposes.
The OS image is small, unbloated and Lean and Mean, where you can add, remove or change packages as you wish.

NanoPi R5S
![NanoPi R5S](https://raw.githubusercontent.com/avafinger/nanopi-r5s-ubuntu-base-minimal/main/nanopi-r5s.jpg)

USB Cameras
![NanoPi R5S - USB Cameras](https://raw.githubusercontent.com/avafinger/nanopi-r5s-ubuntu-base-minimal/main/nanopi-r5s-cameras.jpg)

**i hope this can be usefull**

* [Introduction](#introduction)
* [Target audience](#target-audience)
* [Yet Another OS Image?](#yet-another-os-image)
* [WIP](#wip)
* [Kernel History](#kernel-history)
* [USB Cameras](#cameras)
* [NPU](#npu)
* [Monitoring tool](#monitoring-tool)
* [Build your own Kernel](#build-kernel)
* [Mini Router](#mini-router)
* [Releases](#releases)
* [Issues](#issues)
* [Acknowledgements](#acknowledgements)
* [References](#references)

## Introduction

This is the Ubuntu 22.04 LTS Image for the **NanoPi R5S 2GB/4GB** with functional hardware features (Kernel).
Image is minimal with some tools already installed. You can switch Kernel version to get most of the board peripherals working. 


## Target audience

You need to setup keyboard, language and everything else with command line, no automation process.
It's for anyone who wants to learn, build and develop packages with the Ubuntu environment. 

- Want to run as multimedia, you have it. 
- Want to run AI applications, you have it. 
- Want to run as mini router (2.5 GBPS), you have it.
- Want to run mainline kernel, you have it.


## Yet Another OS Image?

With the OS Image you can have access to the following features:

* Hardware Acceleration (GPU)
* Hardware Decoder (VPU)
* 2x 2.5 Gbps (eth0 and eth1)
* RKNPU for AI (NPU)
* USB camera (v4l2)

## WIP

This is a Work In Progress, things that do not work may be fixed in the future, with no timeline, and no guarantee. Use as is.

## Kernel history

Kernel will be added as it is a WiP, ideal for testing, developing and checking functionality.

* **v1 is Kernel 5.10.110**

## USB Cameras


## NPU

to be created.

## Monitoring tool

to be created.

## Build your own Kernel

to be created.

## Mini Router

to be created.


## Releases

to be created.

## Issues

* Hardware encoder (VPU)
* Wlan (Native Gigabit Ethernet)
* gstreamer (wip)


## Acknowledgements

I would like to thanks FriendlyElec for the sample and JeffyCN for his work on RK platform.

## References

* https://github.com/friendlyarm/
* https://github.com/JeffyCN/

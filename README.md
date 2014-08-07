ROS 2.0 Embedded
===============

This GitBook documents the ROS 2 implementation for embedded devices. ROS 2 for embedded devices is being implemented _from scratch_ to provide an open alternative in the embedded world for ROS 2, the next generation of the Robot Operative System framework. In a nutshell, ROS 2 for embedded systems has the following architecture:

| Ros client nano library API|
|--------|
| DDS (tinq)|
| RTPS (tinq)|
| matching layer|
| FreeRTOS|
| Hardware|

Refer to [this repository]() for the code.

[Chapter 1: Background](background/README.md) provides a background research and comparison betweem different technologies that we looked into when designing ROS 2 for embedded systems. [Chapter 2: ROS 2 embedded](dds/README.md) will describe and document the implementation of ROS 2. [Chapter 3: Using ROS 2 on embedded](using_nanodds/README.md) will show how to use ROS 2 through a set of tutorials and examples.

This work has been performed at the [Open Source Robotics Foundation, Inc.](http://osrfoundation.org/).

![](http://osrfoundation.org/assets/images/osrf_masthead.png)


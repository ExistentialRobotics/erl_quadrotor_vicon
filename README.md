# Overview
This repository contains a modified version of the [vicon_bridge](https://github.com/ethz-asl/vicon_bridge) package and [KumarRobotics/vicon](https://github.com/KumarRobotics/vicon) package. The package allows for the integration of Vicon motion capture system with ROS. It provides a ROS interface for Vicon DataStream SDK. This modified version is a work in progress and there may be future changes. Please use with caution. 

# Installation 
To install the ```erl_quad_vicon``` package, clone this repository and build it using Catkin:
```
$ cd ~/catkin_ws/src
$ git clone https://github.com/ExistentialRobotics/erl_quad_vicon.git
$ cd ..
$ catkin build
```

# Example usage  
- Launch ```erl_vicon.launch``` from ```vicon_bridge``` 
```
$ roslaunch vicon_bridge erl_vicon.launch model=robot_1 datastream_hostport=192.168.30.152:801 
```

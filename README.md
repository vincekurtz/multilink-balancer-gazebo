# Gazebo ROS Double Pendulum

A simple example of simulating a multi-link balancer with a foot. Based on the [Gazebo ROS Demos](https://github.com/ros-simulation/gazebo_ros_demos).

## Tutorials

[ROS URDF](http://gazebosim.org/tutorials/?tut=ros_urdf)

## Quick Start

Rviz:

    roslaunch multilink_balancer_description multilink_balancer_rviz.launch

Gazebo:

    roslaunch multilink_balancer_gazebo multilink_balancer_world.launch

Example of Moving Joints:

    rostopic pub /multilink_balancer/joint1_torque_controller/command std_msgs/Float64 "data: 5"


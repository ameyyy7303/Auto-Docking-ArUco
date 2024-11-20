# Auto-Docking-ArUco

# ROS2 
[![yaw-hidden-gif-1.gif](https://i.postimg.cc/mDBgn4R9/yaw-hidden-gif-1.gif)](https://postimg.cc/zL2NL9yD)

## Overview
This ROS2 package provides an automated docking solution using Aruco markers for precise positioning and orientation of robotic platforms. It employs a camera-based system to detect Aruco markers and aligns the robot for docking, considering the rotational alignment along the Z-axis.

## Features
- **Kalman Filter**: Implements a Kalman filter to improve marker detection reliability and prediction accuracy.
- **Aruco Marker Detection**: Uses a camera to detect Aruco markers and obtains the pose for alignment.
- **Z-Axis Rotation Alignment**: Accounts for the rotational component around the Z-axis for accurate docking.
- **Marker Loss Prediction**: Predicts the marker's location during occlusions or loss of sight, based on the robot's current velocity and angular velocity.
- 



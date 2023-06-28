# ROS2_Autonomous_Mobile_Robot_With_Object_Tracking


This repository contains the code and resources for an autonomous mobile robot capable of object tracking.

## Overview

The Autonomous Mobile Robot with Object Tracking project aims to demonstrate the capabilities of a mobile robot to autonomously navigate its environment and track specific objects. The robot utilizes a combination of sensors, such as a camera and range sensors, to perceive the environment and make decisions based on the detected objects.

## Features

**- Autonomous navigation:** The robot can navigate its environment without human intervention, avoiding obstacles and reaching a target destination.  
**- Object detection and tracking:** The robot can detect and track specific objects of interest using computer vision or sensors.  
**- Real-time feedback:** The robot provides real-time feedback through a user interface, displaying the tracked objects and navigation status.  

## Prerequisites

- Software requirements:
  - ROS (Robot Operating System) installed on the robot.
  - Python and required dependencies installed.
  - Computer vision libraries (e.g., OpenCV) installed.
  
## Installation


1. Clone this repository:

2. Navigate to the project directory:
   cd Autonomous_Mobile_Robot_With_Object_Tracking
3. Build and install the ROS packages:
   cd ros_ws
   colcon build --symlink-install
   source ros_ws/install/setup.bash


## Launching the robot in Gazebo

Use command:
Ros2 launch mobile_robot launch_sim.launch.py 

Robot model will be spawn in gazebo
You can control it using command ros2 run teleop_twist_keyboard teleop_twist_keyboard 
Since it’s a differential drive robot u can control it using the following keys mention in teleop_keyboard to turn left, right, forward and backward

## About our robot:

Here we created a manipulator with four wheel and arm which contains 3r arm and camera as end-effector which contains in description1.
If you want to run it copy paste those files in the description folder (delete current files containing in folder)

## To Launch in Rviz:

### Run Command:
rviz2

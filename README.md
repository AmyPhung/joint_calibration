# Joint Calibration

# Build Status
[![Build Status](https://api.travis-ci.com/AmyPhung/joint_calibration.svg?branch=master)](https://travis-ci.com/github/AmyPhung/joint_calibration)

## Dependencies
+ https://github.com/versatran01/apriltag.git

## Setup
+ `cd ~/catkin_ws/src`
+ `git clone https://github.com/AmyPhung/arm_slam_calibration`
+ `cd ~/catkin_ws/`
+ `rosdep install -iry --from-paths src`


## Usage
+ Start apriltag detection `roslaunch apriltag_ros continuous_detection.launch`

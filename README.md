moveit_pr2
==========

MoveIt! Packages for PR2

## Build Status

indigo-devel branch: [![Build Status](https://travis-ci.org/ros-planning/moveit_pr2.png?branch=indigo-devel)](https://travis-ci.org/ros-planning/moveit_pr2)

## PR2 MoveIt! Tutorials

Note that the PR2 tutorials have been moved to the consolidated [moveit_tutorials](https://github.com/ros-planning/moveit_tutorials) with the rest of the documentation

```
sudo apt install ros-kinetic-moveit-visual-tools 
sudo apt install ros-kinetic-pr2-gazebo ros-kinetic-pr2-moveit-plugins
roslaunch pr2_gazebo pr2_empty_world.launch 
roslaunch pr2_moveit_config move_group.launch 
roslaunch pr2_moveit_config moveit_rviz.launch config:=1
```

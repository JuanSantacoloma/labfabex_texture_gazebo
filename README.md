# Simulation of LabFabEx

This package of ROS have all the information needed for the following result (distro: Melodic):

![result of this package](/result_package.png)

## Building this package
### Steps:
- Clone this repo in your workspace.

`cd ~/catkin_ws/src`

`git clone https://github.com/JuanSantacoloma/labfabex_texture_gazebo `

- Build labfabex_texture_gazebo

  -If you use catkin_make:

  `cd ~/catkin_ws`

  `catkin_make`

  -If you use catkin tools:

  `cd ~/catkin_ws`

  `catkin build labfabex_texture_gazebo`

-Source bash

`source ~/catkin_ws/devel/setup.bash`

- Run this launch

`roslauch labfabex_texture_gazebo labfabex.launch`

- Enjoy
# ROS Robotics by Example

Implementation of the examples on the chapters of the book: ROS Robotics By Example

The road so far:
 - URDF model
 - Rviz config file
 - Basic launcher file

Next step: Add differential drive, so we can control the robot by teleop.


## How to install:

 - Create a directory and cd into it
 - Clone this repo with ```git clone git@github.com:lagartoxa/ros-robotics-by-example.git src```
 - Run ```$ catkin_make```
 - Source the setup file with ```$ source {your_directory}/devel/setup.zsh # or setup.bash if you don't use zsh```


## How to run:

The complete robot is the one at urdf/dd_robot_complete.urdf. All others were the steps followed on the book and were kept for the history

 - Running the robot on rviz
```$ roslaunch ros_robotics dd_robot_rviz.launch model:=dd_robot_complete.urdf```

 - Running the robot on gazebo
```$ roslaunch ros_robotics dd_robot_gazebo.launch model:=dd_robot_complete.urdf```


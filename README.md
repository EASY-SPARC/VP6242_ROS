## ROS package for Denso VP6242

### Dependencies
```
sudo apt install ros-melodic-moveit
sudo apt install ros-melodic-ros-control
sudo apt install ros-melodic-ros-controllers
sudo apt install ros-melodic-joint-state-publisher-gui
```

### How to run

You can run RViz environment with:
```
roslaunch vp6242_description display.launch
```

You can run Gazebo environment with:
```
roslaunch vp6242_gazebo vp6242.launch
```

### Further information
- https://densorobotics.com/content/user_manuals/19/005929.html
- http://wiki.ros.org/ros_control

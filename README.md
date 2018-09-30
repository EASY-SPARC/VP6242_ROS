## ROS package for Denso VP6242

### Changes
- Fixed Eigen dependencies
- Fixed tranmission control issues
- Packages for ros_control working

### How to run

You can run RViz environment with:
```
roslaunch vp6242_description display.launch
```

You can run Gazebo environment with:
```
roslaunch vp6242_gazebo vp6242.launch
```

### To Do
- Add Robotiq Gripper support
- Learn how to use controller_nterface
- Learn how to use Ik-Fast



### Further information
- https://densorobotics.com/content/user_manuals/19/005929.html
- http://wiki.ros.org/ros_control
- http://docs.ros.org/kinetic/api/moveit_tutorials/html/doc/ikfast/ikfast_tutorial.html

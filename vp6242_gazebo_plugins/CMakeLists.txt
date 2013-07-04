cmake_minimum_required(VERSION 2.8.3)
project(vp6242_gazebo_plugins)

find_package(catkin REQUIRED COMPONENTS 
    gazebo_ros
)

# Find gazebo
include (FindPkgConfig)
if (PKG_CONFIG_FOUND)
    pkg_check_modules(GAZEBO gazebo)
endif()

include_directories(include ${catkin_INCLUDE_DIRS} ${GAZEBO_INCLUDE_DIRS})

# Build whatever you need here
#add_library(...) # TODO

catkin_package(
    DEPENDS 
        gazebo_ros
    CATKIN_DEPENDS
    INCLUDE_DIRS 
    LIBRARIES 
)
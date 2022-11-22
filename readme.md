# ROS

### installation
install ros1 using follow url
http://wiki.ros.org/noetic/Installation

add the source file in bashrc
``
source /opt/ros/noetic/setup.bash
``

### Workspace setup
create a folder inside home
``catkin_ws``
create folder src inside ``catkin_ws/src``

inside catkin_ws directory run 
```
cd ~/catkin_ws
catkin_make
```
 it will generate 3 directories ``build``  ``devel``  ``src``
 
 souce the bash file
 ```
 nano ~/.bashrc
 ```
 
 add the source file in bashrc 
``source ~/catkin_ws/devel/setup.bash``

### create package for 
 

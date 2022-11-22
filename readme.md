# ROS

### Installation
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

### Create package for 
goto
```
cd ~/catkin_ws/src
catkin_create_pkg my_robot_controller rospy roscpp turtlesim
```
``CMakeLists.txt``  ``my_robot_controller``

install vscode (sudo snap install code --classic)

### build package
```
cd ~/catkin_ws
catkin_make
```


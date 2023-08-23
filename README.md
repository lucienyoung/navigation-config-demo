# navigation-config-demo
The example of ros-navigation config file. The relavant parameter details can be found at [ros-navigation wiki](http://wiki.ros.org/navigation).
## How to install ros-navigation
Take the ROS Melodic as an example.
```
<!--install dependencies--/>
sudo apt install ros-melodic-navigation*
sudo apt remove ros-melodic-navigation

//create new ros workspace for further maintenance
cd ~/catkin_ws/src/
git clone https://github.com/ros-planning/navigation.git
cd navigation
git branch //check whether the code version is melodic
git checkout melodic-devel //otherwise, switch to the required branch

//compile
cd ~/catkin_ws/
catkin_make
```

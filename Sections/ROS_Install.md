Installing ROS
==============
http://wiki.ros.org/lunar/Installation/Ubuntu

Configure Ubuntu Repositories
-----------------------------
https://help.ubuntu.com/community/Repositories/Ubuntu

Configure to allow "restricted", "universe", and "multiverse"
**Image Software tab**

Setup sources
-------------
Setup PC to accept software from packages.ros.org
**sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'**

Setup keys
----------
**sudo apt-key adv --keyserver hkp://ha.pool.sks-keyservers.net:80 --recv-key 421C365BD9FF1F717815A3895523BAEEB01FA116**

Install
-------
First update Debian package index
**sudo apt-get update**

Install Desktop-Full install (ROS, rqt, rviz, robot-generic libraries, 2D/3D simulators, navigation and 2D/3D perception
**sudo apt-get install ros-lunar-desktop-full**

Initialize rosdep
-----------------
**sudo rosdep init**
[sudo] password for benrjg: 
Wrote /etc/ros/rosdep/sources.list.d/20-default.list
Recommended: please run

	rosdep update

**rosdep update**

Environment setup
-----------------
echo "source /opt/ros/lunar/setup.bash" >> ~/.bashrc
source ~/.bashrc

Dependencies for building packages
----------------------------------
sudo apt-get install python-rosinstall python-rosinstall-generator python-wstool build-essential

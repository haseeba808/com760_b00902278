# com760_b00902278my
ROS 1/2 by haseeba 

by sir ref but found not good {sudo apt update sudo apt upgrade sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list ' (the above statement is all one line with a space after the >) sudo apt install curl curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add-

sudo apt update sudo apt install ros-kinetic-desktop-full echo "source /opt/ros/kinetic/setup.bash">> ~/.bashrc source ~/.bashrc sudo apt install python-rosdep python-rosinstall python-rosintall-generator python-wstool build-essential sudo rosdep init rosdep update

roscore

rosrun turtlesim turtlesim_node

rosrun turtlesim turtle_teleop_key

gazebo yeh lagah kar dekhlay than copy paste hota hai warna direct link open kar leh drive ka link seh download it sudo apt-get install virtualbox-guest-utils} https://aniekan.blog/2022/01/24/creating-your-first-package-in-ros/ https://www.theconstructsim.com/ros-beginner-mistakes-1-missing-execute-permission-on-the-python-file/

#!/usr/bin/env python

import rospy from turtlesim.msg import Pose from geometry_msgs.msg import Twist from math import pow, atan2, sqrt



sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list' sudo apt-key adv --keyserver hkp://ha.pool.sks-keyservers.net:80 --recv-key 0xB01FA116 sudo apt-get update sudo apt-get install ros-kinetic-desktop-full sudo rosdep init rosdep update source /opt/ros/kinetic/setup.bash

echo "source /opt/ros/kinetic/setup.bash" >> ~/.bashrc

source ~/.bashrc

sudo apt-get install python-rosinstall roscore

rosrun turtlesim turtlesim_node

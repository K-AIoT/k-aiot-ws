
# K-AIoT Robot Development
Description coming soon! 


## Installation

Dowload the robot code from: https://drive.google.com/file/d/1azgsnl7ia1m9O_sUwXsb6Muvg0N-CXgI/view?usp=share_link. This zip-file contains packages that we will use. 



```bash
  npm install my-project
  cd my-project
```
    
## Table of content

[Installation](#installation)\
[Virtual Machine](#Virtual-Machine)\
[ROS Melodic Installation](#ROS-Melodic-Installation)


## Virtual Machine

Pick a software of you're own choice to run a virtual machine. 

Follow the installation guide for the choosen software. 

Dowload the disk file at: https://releases.ubuntu.com/18.04/. 

## ROS Melodic Installation
When you have successfully installed Ubuntu 18.04, you can follow the steps bellow to get ROS installed. 

The full guide can be followed at: http://wiki.ros.org/melodic/Installation/Ubuntu 

1. Setup your computer to accept software from packages.ros.org.
```bash
sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'
```
2. Setup your keys.
```bash
sudo apt install curl # if you haven't already installed curl
curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -
```

3. First, make sure your Debian package index is up-to-date:
```bash
sudo apt update
```

4. Desktop-Full Install: (Recommended) : ROS, rqt, rviz, robot-generic libraries, 2D/3D simulators and 2D/3D perception
```bash
sudo apt install ros-melodic-desktop-full
```

5. To find available packages, use:
```bash
apt search ros-melodic
```

6. It's convenient if the ROS environment variables are automatically added to your bash session every time a new shell is launched:
```bash
echo "source /opt/ros/melodic/setup.bash" >> ~/.bashrc
source ~/.bashrc
```

7. To install this tool and other dependencies for building ROS packages, run:
```bash
sudo apt install python-rosdep python-rosinstall python-rosinstall-generator python-wstool build-essential
```

8. Before you can use many ROS tools, you will need to initialize rosdep. rosdep enables you to easily install system dependencies for source you want to compile and is required to run some core components in ROS.
```bash
sudo apt install python-rosdep
```

10. With the following, you can initialize rosdep.
```bash
sudo rosdep init
rosdep update
```
## Documentation
Comming soon! 

[Code](https://linktodocumentation)




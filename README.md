# Capstone_design


## Software requirements
* Ubuntu 20.04 LTS on the remote PC
* ROS1 Noetic Ninjemys


## Installing ROS on the remote PC
```
ubuntuvm@ubuntuvm:~$ sudo apt update
Reading package lists... Done
ubuntuvm@ubuntuvm:~$ sudo apt upgrade      
Reading state information... Done
ubuntuvm@ubuntuvm:~$  wget https://raw.githubusercontent.com/ROBOTIS-GIT/robotis_tools/master/install_ros_noetic.sh
2024-11-19 13:22:38 (13.8 MB/s) - ‘install_ros_noetic.sh’ saved [3105/3105]
ubuntuvm@ubuntuvm:~$ chmod 755 ./install_ros_noetic.sh
ubuntuvm@ubuntuvm:~$ bash ./install_ros_noetic.sh
[Note] Target OS version  >>> Ubuntu 20.04.x (Focal Fossa) or Linux Mint 21.x
[Note] Target ROS version >>> ROS Noetic Ninjemys
####
#### Running command: "make -j4 -l4" in "/home/ubuntuvm/catkin_ws/build"
####
[Set the ROS evironment]
[Complete!!!]


```
## Creeating a workspace
```
ubuntuvm@ubuntuvm:~$ cd ~/
ubuntuvm@ubuntuvm:~$ mkdir -p autonomous_tb3_ws/src
ubuntuvm@ubuntuvm:~$ cd autonomous_tb3_ws/
ubuntuvm@ubuntuvm:~/autonomous_tb3_ws$ cd src
ubuntuvm@ubuntuvm:~/autonomous_tb3_ws/src$

```

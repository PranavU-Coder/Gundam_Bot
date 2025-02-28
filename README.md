# Gundam_Bot (Guide to ROS2 usage as well)
Personal experiment to test out using my knowledge of ROS2 and Gazebo (both of which I'm learning)

👋 Hello fellow robotics enjoyer, With this repository I aim to config the files in a way you can setup a similar bot for your own needs 
Before we start working on the bot, ensure necessary packages are installed. I am using Jazzy Jalisco as it is the latest version of ROS2
you can use other versions as well such as rolling , iron etc. so be sure to replace the distro name from 'jazzy' to '{your_distro_name}'
```bash
source /opt/ros/jazzy/setup.bash
```

this command creates an underlay 

these two packages are quite important for the program and rviz to work :-

```bash
sudo apt install ros-jazzy-joint-state-publisher
sudo apt install ros-jazzy-joint-state-publisher-gui
```

xacro is also a useful tool which will come in handy for this program

```bash
sudo apt install ros-jazzy-xacro
```


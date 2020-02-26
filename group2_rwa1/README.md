## Authors

* **Rachith Prakash** [GitHub](https://github.com/RachithP)
* **Raj Prakash Shinde** [GitHub](https://github.com/RajPShinde)
* **Shubham Sonawane** [GitHub](https://github.com/shubham1925)
* **Chinmay Josji** [GitHub](https://github.com/Chinj17)
* **Shesh Mali** [GitHub]()

## Overview
A Package to read logical camera data in 2019 Ariac Environment

## Dependencies
1. Ubuntu 18.04
2. ROS Melodic

## Build
Steps to build
```
mkdir -p ~/catkin_ws/src
cd ~/catkin_ws/
catkin_make
source devel/setup.bash
cd src/
git clone -b rachith https://github.com/ENPM809B/RWA2.git
cd ~/catkin_ws/
catkin_make --only-pkg-with-deps group2_rwa1
```
## Run
To launch the environment and run the required node
```
cd ~/catkin_ws
source devel/setup.bash
roslaunch group2_rwa1 group2-rwa1.launch
```

On Another terminal run
```
rosrun group2_rwa1 ariac_example_node
```

# Project_3

To build
```
cd catkin_ws
catkin_make
```
To run

Terminal 1
```
source devel/setup.bash
roslaunch my_robot world.launch 
```
Terminal 2
```
source devel/setup.bash
roslaunch project_3 amcl.launch
```
Terminal 2
```
source devel/setup.bash
rosrun teleop_twist_keyboard teleop_twist_keyboard.py 
```
The Localized robot

<img src="https://github.com/PranaliDesai/Project_3/blob/master/Localized_robot" width="300">


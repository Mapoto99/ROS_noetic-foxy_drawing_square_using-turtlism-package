# ROS_noetic/foxy_drawing_square_using-turtlism-package

## Drawing a square using turtlesim package in ROS noetic:
1- Download turtlesim package typing this in the terminal:
```
sudo apt install ros-noetic-turtlesim
```
2- close the window, and open three terminals in the same window by clicking on this button on the top left of the terminal window

![Screenshot from 2024-07-05 14-47-12](https://github.com/Mapoto99/ROS_noetic-foxy_drawing_square_using-turtlism-package/assets/174211031/7621e899-6cd0-48ed-aeb4-5a6076c550db)

3- In the first  window type:
```
roscore
```
4- In the second window type these respectively:

*the code below will display another different window showning a turtle*
```
rosrun turtlesim turtlesim_node
```
5- In the third window type:
```
rosrun turtlesim draw_square
```
and to quit the loop press this on the key board and the turtle will stop drawing
```
CTRL + C
```
## Drawing a square using turtlesim package in ROS foxy:
### *To switch between ROS noetic and foxy do the following:*
  1- run this:
```
  gedit ~/.bashrc
  ```
  it will display another window
  go to the most bottom and you will find:
  ```
  source /opt/ros/noetic/setup.bash
  ```
  change it to:
  ```
  source /opt/ros/foxy/setup.bash
  ```
then to start please follow:
1-
```
ros2 core
```
2-
```
ros2 run turtlesim turtlesim_node
```
3-
```
ros2 run turtlesim draw_square
```
# Thank you

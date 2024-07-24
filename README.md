# Hadi-ROS-W3-Task-1
Attack of the Robot (Arm)!

## Creating a workspace in catkin.
We start by creating the directory for our catkin workspace with the following <br />
```mkdir -p ~/catkin_ws/src``` <br />
which simply makes two empty folders for us to organize our work in <br />
we then navaigate to our newly created directory to make it an actual workspace using <br />
```catkin_make``` <br />
and finally, to make using the workspace easier we can put it alongside ROS in .bashrc like this <br />
```gedit ~/.bashrc``` <br />
![image](https://github.com/user-attachments/assets/32966e23-4dc4-45f4-bcc3-9e3660c6bdff)
## Setting up the pre-requisites.
We start by running this in our workspace
```rosdep install --from-paths src --ignore-src -r -y``` <br />
for ROS noetic <br />
```
sudo apt-get install ros-noetic-moveit
sudo apt-get install ros-noetic-joint-state-publisher ros-noetic-joint-state-publisher-gui
sudo apt-get install ros-noetic-gazebo-ros-control joint-state-publisher
sudo apt-get install ros-noetic-ros-controllers ros-noetic-ros-control
```
 <br />
 afterwards, we navigate to ~/catkin_ws/src and download a copy of the arduino_robot_arm repository using git <br />
 finally, we go to the original catkin_ws and use (catkin_make) to update the workspace after the changes
 ## Simulating the robot arm.
 

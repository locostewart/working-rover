## Requirements: 
Have Linux installed.

## Usage instructions:

#### 1) Making a Workspace
(Note--If you already have a workspace you are using you can skip this step.  None of the code is dependent on the name of the workspace.
In linux, make a new workspace with the following commands:

```
source /opt/ros/jazzy/setup.bash
mkdir -p ~/ros2_ws/src
cd ~/ros2_ws/src
```

Replace "ros2_ws" with whatever you want your workspace to be called. Make sure to remember it though because you will need it later.

#### 2) Setting up the file
Put the main folder in this github into your src folder of your workspace.  It's easiest to do this through the file folder system of your computer instead of doing it through linux because honestly I'm not sure how.


<img width="1043" height="43" alt="Screenshot 2025-11-13 121203" src="https://github.com/user-attachments/assets/14116032-685d-4530-8393-d900b485e3fc" />

Here's an image of the file path.  Note that my workspace is called ws_4.

#### 3) Opening the file
In linux, run the commands one at a time:

```
cd ros2_ws
```
Replace "ros2_ws" with your workspace name.  If you're already in your workspace you can skip this step.
```
source install/setup.bash
```
```
colcon build
```
```
ros2 launch ROS_description gazebo.launch.py
```





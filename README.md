## ROS package for Lab 3 - Data used from Glennan 5th Floor - ROS Bagged
### Alan Goodloe (amg284)

#### To set up project, run this command to call the launch file:
`roslaunch navvis_description display.launch`  
  
The launch file has the following args:

- use_xacro

use_xacro (Set to False as default):
Uses the newer xacro file if true, while using the urdf file if false. 
  
- use_robot_state_publisher

use_robot_state_publisher (Set to true as default):  
Launches use_robot_state_publisher when true, and does not when false.

- use_sim_time

use_sim_time (Set to true as default):  
Set's use_sim_time parameter to true/false
  

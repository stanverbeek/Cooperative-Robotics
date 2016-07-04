## Launch files

### One robot scenario
This scenario will start up one Rosbee robot simulation in Gazebo. The rostopics are now active of this robot (laser scan, wheel control, etc.). It positionate itself somewhere in the .world file and the next thing to do is starting SLAM Gmapping. 

### Three robots scenario
This scenario will start up the same thing as in one robot scenario, the only diffence is that this scenario includes three Rosbee robots in Gazebo. 

### SLAM Gmapping
This launch file will start writing the laser scan data to its rostopic (/map). This 2D map will be created while the SLAM Gmapping node is running in the terminal and it can be visualized in Rviz.

### World
The launch file of the world will simply start up the 3D environment in the Gazebo simulation. In this case we've made a maze out of boxes.

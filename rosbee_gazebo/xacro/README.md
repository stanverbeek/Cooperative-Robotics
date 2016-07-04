## XACRO files
### Rosbee robot parts
The xacro files will scale/link every part of the robot (for example: the dimensions of the base plate and link this to the swivel wheel) and it also links the rostopics to the parts of the robot (for example: it links the cmd_vel topic to the wheels of the robot). 

### Camera/Laser sensor
These sensors are located here, in this xacro script it will simulate the sensors. These xacro scripts will be linked to the main Rosbee xacro file, in this way the sensors will be used in the simulation. 

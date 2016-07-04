## Rosbee in Gazebo
To control the simulation environment, there are different folders (launch, meshes, worlds and xacro). This folders include documents that can start/run the Rosbee simulation environment. 

### Launch folder:
In this folder you can find the .launch files. When you start this kind of file with a command in the ternminal, the activities of that specific .launch file will start up. 

### Meshes folder:
The .stl files are located in this folder. These files representate the physical Rosbee robot, because these 3d drawings will show up in the simulation of the Rosbee robot.

### Worlds folder:
A .world file will attach a environment with 3D obstacles in it. In this way it's possible to make a map with the Rosbee robot, otherwise there are no objects to scan and to presentate in the created map. 

### Xacro folder:
The files in this folder are the files that combines the 3D drawings of the robot, the world file, the controlling system, etc. 

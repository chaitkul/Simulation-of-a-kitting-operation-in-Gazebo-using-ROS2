# Simulation-of-a-kitting-operation-in-Gazebo-using-ROS2

Project Description:

1. The project is about kitting operation, which is the process of picking up parts from bins, placing them in a tray located on an automated guided vehicle (AGV), and submitting the AGV. The environment image is attached below.

![image](https://github.com/chaitkul/Simulation-of-a-kitting-operation-in-Gazebo-using-ROS2/assets/127642282/00c31b39-9a41-4d36-b24a-6073ddd597f0)

2. The ﬁnal product is called a kit, (see below)

![image](https://github.com/chaitkul/Simulation-of-a-kitting-operation-in-Gazebo-using-ROS2/assets/127642282/e7f96296-f165-45db-a0fe-86a36b7d88dc)

3. The first part focuses on reading one order published on the ROS topic, locate trays and parts needed for the order, and logs the parts and tray locations in the terminal.

4. The second phase of the project is to task the robot to complete the kit. The ﬂoor robot is the robot mounted on the linear rail and can perform kitting.Before completing a kit the program needs to ﬁgure out which Order out of the four Orders to complete.

5. The project involves implementing a system to automate order fulfillment in a warehouse using robots, cameras, and AGVs. The process begins with the system reading and processing orders, determining the required items, quantities, and any specific instructions. Cameras are strategically placed to capture data on the items and their locations, which provide the pose of the object. The next step is to retrieve the necessary components based on this data, gather specific information about these parts, and place them on a tray. Subsequently, the tray is positioned on an AGV, and the AGV is dispatched to the warehouse.


Video Link: https://drive.google.com/file/d/1iNMIiaK27dxdSgKWbZv82omdj3_b7xkv/view?usp=drive_link


### Weekly Journal Entry: 6/23 - 6/28

**Monday:**
Today, I focused on testing the motors and encoders for the robot. I used the `test_motors` utility to spin the motors forward and backward, observing their linear and angular velocities as well as the distance to full stop. I ensured the motors were running in the correct direction and calibrated the RPM reading using a digital tachometer. Additionally, I connected the bottom USB 3.1 port on the Raspberry Pi to the USB C port on the general driver board. After stopping the robot-boot service, I built and uploaded the firmware for the motors. I also tested the other sensors using the `test_sensors` utility and connected the LiDAR sensor, visualizing the laser scans with ROS2.

**Tuesday:**
I successfully controlled the robot remotely from the host machine by configuring the Data Distribution Service (DDS) networking. I ensured both the robot and the host computer were on the same network, which required modifying the `cyclonedds.xml` file to include peer IP addresses. I added the necessary line to the `.bashrc` file and tested the connection by examining available ROS2 topics. Additionally, I addressed network issues on my virtual machine by switching to a bridge connection in the UTM network settings and using a remote access point provided by Dr. Scott.

**Wednesday:**
Today was dedicated to solving the ROS_DOMAIN_ID issue. Since all robots were using the same access point, one host machine was controlling all robots. To address this, we attempted to establish unique IDs for each robot to control them individually. Despite several attempts, we faced challenges in setting unique domain IDs, and I decided to move on to testing SLAM navigation.

**Thursday:**
I focused on creating a map for SLAM navigation. Using RViz, I visualized the robot and drove it manually to cover its area of operation. However, the map generated was not satisfactory, leading me to move the LiDAR to the front of the robot. This adjustment did not resolve the issue, so I used another working robot to create a map successfully. I documented this process and prepared for autonomous navigation tests.

**Friday:**
I moved on to autonomous navigation, loading the map created yesterday. I modified the `navigation.launch.py` file to include the new map and used RViz to visualize the robot remotely. After setting the robot's initial pose in RViz, I sent a goal pose for autonomous navigation. Although there were initial routing issues, I eventually achieved autonomous navigation using a different robot. Next, I plan to develop visual SLAM, fix the LiDAR robot, and resolve issues with multiple robots on the same network.

### Summary for the Week

**Accomplishments:**
- Tested and calibrated motors and encoders.
- Controlled the robot remotely from the host machine.
- Configured DDS networking for ROS2 communication.
- Created and tested SLAM maps.
- Achieved initial autonomous navigation.

**Results Achieved:**
- Successfully calibrated motor RPM with a digital tachometer.
- Established remote control via DDS networking.
- Created a functional SLAM map with another robot.
- Achieved basic autonomous navigation.

**Findings:**
- Challenges with network settings on virtual machines.
- Difficulties in setting unique ROS_DOMAIN_IDs.
- Importance of LiDAR placement for accurate mapping.

**Algorithms Used:**
- SLAM for mapping.
- DDS for ROS2 communication.
- Teleop_twist_keyboard for remote control.

**Issues and Frustrations:**
- Motor wiring issues.
- Network configuration challenges.
- ROS_DOMAIN_ID conflicts.
- Unreliable mapping with initial LiDAR placement.

**Relevant Experiences and Insights:**
- Importance of proper network setup for ROS2.
- Effective use of remote access points for stable connections.
- Need for precise sensor placement for accurate SLAM.

### Weekly Journal Entry: 7/8 - 7/12

Throughout the week, efforts were focused on hardware assembly, software configuration, and integration for autonomous navigation and visual SLAM. Significant progress was made in setting up the Jetson Nano and RealSense camera, despite encountering several technical challenges.

**Accomplishments:**

- **RealSense Camera Integration**: Successfully got the RealSense camera working, which is crucial for implementing visual SLAM.
- **Jetson Nano Setup**: Despite initial issues with burning the correct image files onto SD cards, a workaround was found by cloning Dr. Scott's working SD and SSD cards, avoiding the deprecated image files.
- **Pointcloud Mapping**: Successfully mapped a pointcloud map using the RealSense camera, laying the groundwork for creating a room map once the robot is operational.
- **Base Assembly of Robot**: Built the base of the robot, pending the delivery of additional parts for completion.
- **Idea Proposal**: Suggested sourcing both LiDAR and camera processing through the Jetson Nano, eliminating the need for a separate Raspberry Pi. This proposal was approved and is now being pursued.

**Results Achieved:**

- **Cloning Success**: Avoided issues with deprecated image files by cloning existing working SD and SSD cards, ensuring smooth operation of the Jetson Nano without further updates.
- **Initial Pointcloud Map**: Created a preliminary pointcloud map using the RealSense camera, which will be expanded once the robot is fully operational.
- **Base Assembly**: Successfully assembled the base of the robot, preparing for the integration of other components.

**Findings:**

- **SD Card Issues**: Identified that using deprecated image files caused corruption in SD cards, highlighting the importance of using up-to-date and compatible software.
- **Integration Efficiency**: Found that integrating both LiDAR and camera processing on the Jetson Nano could streamline operations and reduce the hardware complexity of the robot.

**Algorithms Used:**

- **Pointcloud Mapping**: Utilized pointcloud mapping algorithms with the RealSense camera to create an initial map of the environment.
- **Docker Configuration**: Attempted to configure Docker containers for running Linorobot, although faced with several issues.

**Issues and Frustrations:**

- **SD Card Corruption**: Faced repeated issues with SD card corruption and deprecated image files, requiring a switch to cloning working cards.
- **Docker Configuration Challenges**: Encountered multiple errors with missing packages and container toolkits when configuring Docker for Linorobot on the Jetson Nano.
- **Delay in Robot Assembly**: Delays in receiving additional parts for the robot halted full assembly, limiting progress in testing and integration.

**Other Relevant Experiences and Insights:**

- **Practical Workarounds**: Learned the value of practical workarounds, such as cloning working SD cards, to overcome technical challenges and continue making progress.
- **Community Engagement**: Shared progress and future plans during a town hall meeting, fostering collaboration and support among peers.

This week’s activities have advanced the project in key areas, particularly in setting up hardware and beginning pointcloud mapping. As we move forward, addressing the remaining challenges with Docker configuration and completing the robot assembly will be crucial for achieving our autonomous navigation and visual SLAM goals.

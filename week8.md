### Weekly Journal Entry: 7/14 - 7/19

This week was dedicated to furthering our work in autonomous navigation and SLAM (Simultaneous Localization and Mapping), with a strong focus on resolving previous technical issues and making significant advancements in robot construction and mapping processes.

**Accomplishments:**

- **Robot Construction Completion**: Finished building the robot, including the correct wiring of all components. This involved careful assembly and verification of each part to ensure proper functionality.
- **SLAM Visualization on Host Machine**: Successfully visualized the SLAM mapping on the host machine by resolving issues with topic listing and dependencies. This achievement allows us to monitor and analyze the SLAM process in real-time.
- **Experimental SLAM Setup**: Progressed in the experimental SLAM project by using Docker containers to run ROS Humble, overcoming the limitations of ROS Galactic. This setup is now more flexible and can handle more complex computations.
- **Room Mapping**: Achieved a functional visual SLAM map of the room after troubleshooting and fixing several hardware and software issues. This milestone is crucial for the next phase of autonomous navigation.

**Results Achieved:**

- **Robot Assembly**: Completed the robot assembly after receiving the final parts and correctly wiring the motor connections. The robot is now fully operational and ready for further testing.
- **SLAM Visualization**: Enabled visualization of SLAM mapping on the host machine by correctly launching the SLAM node on the robot first and ensuring all topics were available. This success allows for a better understanding and debugging of the SLAM process.
- **Room Map Creation**: Successfully mapped the room using the visual SLAM setup and began testing the localization features. This map will serve as a foundation for future navigation tasks.

**Findings:**

- **ROS Version Compatibility**: Identified that ROS Galactic on Ubuntu 20.04 was not compatible with the required SLAM packages, necessitating a switch to ROS Humble on Ubuntu 22.04 via Docker. This finding highlights the importance of maintaining compatibility between software versions.
- **Hardware Vulnerabilities**: Discovered that incorrect wiring can damage components such as the Waveshare board, which was fixed by replacing the board. This incident emphasizes the need for careful handling and assembly of hardware components.

**Algorithms Used:**

- **Visual SLAM**: Utilized visual SLAM algorithms for mapping and localization, enabling the robot to understand and navigate its environment.
- **Teleoperation**: Implemented teleoperation scripts to move the robot and visualize its movements. These scripts are essential for manually controlling the robot during testing phases.

**Issues and Frustrations:**

- **ROS Dependencies**: Faced challenges with missing dependencies and version conflicts in ROS, requiring multiple troubleshooting steps. This was time-consuming and required extensive research and problem-solving.
- **Hardware Damage**: Encountered issues with damaged components due to incorrect wiring, causing delays in progress. This setback required careful diagnosis and replacement of the faulty parts.

**Other Relevant Experiences and Insights:**

- **Collaborative Problem-Solving**: Worked closely with Dr. Scott to resolve issues related to ROS versions and hardware setup, highlighting the importance of collaboration in overcoming technical challenges. This teamwork was crucial for making progress.
- **Detailed Documentation**: Created comprehensive documentation to replicate the work done, ensuring that future troubleshooting and setup processes are streamlined. This documentation will be invaluable for anyone looking to reproduce or build upon our work.

**Personal Reflections:**

This week has been highly productive, with critical milestones achieved in robot assembly and SLAM mapping. Despite the technical challenges, the collaborative efforts and systematic troubleshooting led to significant progress. Moving forward, the focus will be on refining the mapping process and ensuring robust localization capabilities.

As we continue our journey, addressing remaining challenges and optimizing the SLAM setup will be essential for achieving our autonomous navigation goals.

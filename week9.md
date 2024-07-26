### Weekly Journal Entry: 7/22 - 7/26

This week focused on overcoming hardware challenges, configuring software for SLAM, and fine-tuning the robot setup to ensure accurate mapping and localization. Significant progress was made, despite encountering various obstacles.

**Accomplishments:**

- **Waveshare Board Configuration**: Successfully installed the NVIDIA Linorobot2 Docker tar image and configured the Waveshare board with the correct settings.
- **Hardware Fixes and Revisions**: Addressed and fixed multiple hardware issues, including replacing a fried Waveshare board and a pin connector extender.
- **Robot Calibration**: Found a temporary solution to reduce noise in SLAM mapping by configuring the visual SLAM algorithm to disable its IMU readings when the LiDAR is not plugged in.
- **Complete Robot Setup**: Fully reassembled the robot, ensuring all components were securely connected and cable management was properly handled.

**Results Achieved:**

- **Working Robot Hardware**: After resolving hardware issues and making necessary revisions to the Linorobot Docker container, the robot is fully operational without hardware concerns.
- **SLAM Mapping**: Enabled visual SLAM mapping, albeit with some noise issues, and began the process of calibrating sensors to improve mapping accuracy.
- **Temporary Calibration Solution**: Adjusted the visual SLAM algorithm to disable IMU readings, allowing mapping to work when only the camera is used.

**Findings:**

- **Hardware Hot Wiring Risks**: Learned the importance of properly insulating wires and avoiding hot wiring to prevent short circuits and hardware damage.
- **Sensor Calibration Challenges**: Identified the need for better calibration between LiDAR and camera sensors to reduce noise in SLAM mapping.
- **IMU Synchronization**: Found that the unite_imu_method parameter in the Realsense2_camera node configuration affects how IMU data is synchronized, with linear interpolation (method 2) being preferred for precise timing and data alignment.

**Algorithms Used:**

- **Visual SLAM**: Utilized visual SLAM algorithms for mapping and localization, configuring parameters to optimize performance.
- **Docker Configuration**: Made revisions to the Linorobot Docker container to ensure consistent and correct configurations for the Waveshare board and other components.

**Issues and Frustrations:**

- **Hardware Damage and Replacements**: Faced setbacks due to hardware damage, requiring careful diagnosis and replacement of components.
- **Noise in SLAM Mapping**: Encountered significant noise in SLAM mapping data, necessitating ongoing efforts to calibrate and synchronize sensors.

**Other Relevant Experiences and Insights:**

- **Collaboration with Dr. Scott**: Worked closely with Dr. Scott to resolve hardware and software issues, underscoring the value of expert guidance and collaboration.
- **Comprehensive Robot Setup**: Successfully reassembled the robot with all components, including motors, encoders, Waveshare board, battery pack, power management system, Jetson Nano, LiDAR, and RealSense camera, all securely connected.

**Personal Reflections:**

This week has been both challenging and rewarding, with critical hardware issues resolved and significant progress made in SLAM mapping. The collaborative efforts and systematic troubleshooting have been essential in overcoming obstacles and advancing the project. Moving forward, the focus will be on further calibrating the sensors to improve mapping accuracy and ensure robust autonomous navigation capabilities.

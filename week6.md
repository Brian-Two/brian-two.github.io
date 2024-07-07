### Weekly Journal Entry: 7/1 - 7/5

Throughout the week, efforts were focused on resolving technical challenges, preparing for a mid-year presentation, refining understanding of core concepts, and making advancements in autonomous navigation and visual SLAM. Despite some setbacks, such as the cancellation of the presentation, valuable insights and progress were made.

**Accomplishments:**

- ROS Domain ID Configuration: Initial attempts to configure the ROS Domain ID for multiple robots were unsuccessful, but a workaround was found by setting up an additional access point, resolving the issue of accessing multiple robots simultaneously.
- Mid-Year Presentation Preparation: Significant time was dedicated to preparing the mid-year presentation, enhancing communication and presentation skills.
- Odometry and Autonomous Navigation: Successfully refined understanding of odometry and the mathematical principles behind encoders. Achieved autonomous navigation with the robot, highlighting the importance of consistent starting points.
- Jetson Nano Familiarization: Began familiarizing with the Jetson Nano to prepare for implementing visual SLAM.

**Results Achieved:**

- Access Point Solution: By adding another access point, the issue of accessing multiple robots at the same time was effectively resolved.
- Autonomous Navigation Success: Achieved smooth autonomous navigation until the robot encountered a grey area on the map. The navigation system worked well in known safe areas.
- nderstanding of Odometry: Improved understanding of how encoders help determine a robot’s position, which is crucial for accurate autonomous navigation.

**Findings:**

- Grey Area Navigation Issue: Discovered that the robot hesitates in areas marked as grey on the map, which it perceives as unsafe. This finding will inform future map adjustments and navigation strategies.
- Importance of Starting Points: Reinforced the importance of starting the robot from the same origin point used during initial mapping for successful autonomous navigation.

**Algorithms Used:**

- Autonomous Navigation Algorithm: Implemented an autonomous navigation algorithm that relies on pre-mapped data and real-time sensor input to navigate the robot safely.
- Odometry Calculations: Utilized odometry calculations to track the robot’s position within its environment based on encoder data.

**Issues and Frustrations:**

- ROS Domain ID Configuration: Faced challenges in getting the ROS Domain ID to work for multiple robots, which remains an area for further research and configuration.
- Grey Area Navigation: Encountered issues with the robot navigating through grey areas on the map, which it deemed unsafe. This limited the robot’s ability to reach the desired destination.

**Other Relevant Experiences and Insights:**

- Workaround Implementation: Learned the value of practical workarounds when faced with technical challenges, which allowed progress to continue despite unresolved configuration issues.
- Community Engagement: Participated in a town hall meeting, which provided an opportunity to check in with peers, share progress, and plan for future activities, fostering a sense of community and collaboration.

This week’s activities have laid a strong foundation for continued progress in our project, particularly in the areas of autonomous navigation and visual SLAM. As we move forward, the insights gained and challenges faced will guide our future efforts and innovations.

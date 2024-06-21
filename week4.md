
Monday:

Workshop Notes:

	•	What is AI?
	•	AI is a branch of computer science that focuses on creating machines capable of performing tasks that typically require human intelligence, such as understanding speech or making decisions.
	•	AI utilizes algorithms and learns by accessing data. This learning process is known as machine learning, where machines improve over time.
	•	What is Generative AI?
	•	Generative AI creates new content by learning from large datasets and can mimic human-like quality.
	•	It includes machine learning models that generate text, images, and other forms of content.
	•	AI Ethics in the Classroom:
	•	Understand the fundamentals of AI.
	•	Recognize the significance of AI in various sectors.
	•	Explore practical applications of AI in education.

Progress:

	•	Continued from last week’s work and successfully installed ROS2 on my virtual machine running Ubuntu 22.04.
	•	Awaiting parts to construct the robot; meanwhile, researching the components and underlying science.

Tuesday:

Steps Completed:

	•	Downloaded the image file and burned it onto a 64GB SDXC card using Balena Etcher.
	•	Reviewed the tutorial on the Linux system.
	•	Utilized the Waveshare General Driver for Robots as a resource, which includes an integrated MPU and connectivity options for sensors and networks.
	•	Began the project by building the power management system with a 2S LiPo battery bank.
	•	Wired the power management to the general driver board using 2 JST 6-pin connectors and 4 3-pin low voltage splicers.
	•	Tested the motors and encoders using the test_motors utility from the GitHub repository for microcontroller firmware. This utility alternates spinning the motors every 10 seconds and displays their velocities and distances to full stop.
	•	Connected the Raspberry Pi’s USB 3.1 port to the USB-C port on the general driver board and ran commands via the terminal.
	•	Learned about general wiring principles and testing through the terminal on the Raspberry Pi.
	•	Identified an issue with one encoder due to improper wiring but plan to fix it after further testing.

Wednesday:

	•	Juneteenth - No Institute

Thursday:

	•	Day at NASA

Friday:

Current Tasks:

	•	Working on fixing the wiring issue for one of the encoders to ensure functionality on both wheels of the robot.
	•	Proceeding with testing other sensors, connecting the Lidar, bringing up the robot, and driving it with a keyboard.

Summary of Accomplishments:

	•	Successfully set up ROS2 on Ubuntu 22.04.
	•	Began assembling the robot by building the power management system and wiring the motors and encoders.
	•	Conducted initial tests on the motors and encoders, learning essential wiring and testing techniques.
	•	Planned to fix the wiring issue with one encoder and continue with further testing and integration of sensors.

Results Achieved:

	•	Established a working ROS2 environment on the virtual machine.
	•	Built the power management system and connected it to the general driver board.
	•	Conducted successful motor tests, though with some issues to resolve.

Findings:

	•	Discovered wiring issues with one encoder.
	•	Gained insights into the wiring principles and the process of testing robots via terminal commands.

Algorithms Used:

	•	Utilized the test_motors utility for testing motor functions, which includes algorithms for spinning motors and measuring their velocities and distances.

Issues Encountered:

	•	Encountered improper wiring issues with one of the encoders, affecting its functionality.
	•	Required rewiring and troubleshooting to ensure all components work correctly.

Insights Gained:

	•	Learned the importance of proper wiring and testing procedures.
	•	Understood the basics of AI and its applications in various sectors, including education.

Next Steps:

	•	Fix the encoder wiring issue.
	•	Test other sensors and integrate the Lidar.
	•	Bring up the robot and test driving it with a keyboard.


Monday:

Today was fast-paced and began with our usual writing workshop, which was just as insightful as last week. My biggest takeaway was learning how to properly analyze rather than summarize. After the writing session, I reviewed some foundational concepts in AI:

	•	What is AI?
	•	AI is a branch of computer science that enables machines to perform tasks that usually require human intelligence, such as understanding speech or making decisions. It uses algorithms and learns from accessing data, a process known as machine learning, where machines improve over time.
	•	What is Generative AI?
	•	Generative AI creates new content by learning from large datasets. It can mimic human-like quality and includes machine learning models that generate text, images, and more.

We also discussed AI ethics in the classroom, focusing on:

	•	Understanding the basics of AI.
	•	Recognizing the importance of AI in various sectors.
	•	Considering practical applications of AI in education.

After the workshop, I continued from where I left off last week and successfully installed ROS2 on my virtual machine running Ubuntu 22.04. Now, I need my parts to construct the robot itself. In the meantime, I will research as much as possible about the parts and the science behind the hardware.

Tuesday:

Today, I made significant progress on the project. Up to now, I have completed these steps:

	•	Downloaded the image file and burned it onto an SDXC card using Balena Etcher. The card needs to be at least 64GB to accommodate the image transfer process.
	•	Reviewed a tutorial on the Linux system.
	•	Utilized the Waveshare General Driver for Robots, which has an integrated MPU and connectivity options for sensors and networks.

I started building the power management system from a 2S LiPo battery bank. I wired the power management to the general driver board using 2 JST 6-pin connectors and 4 3-pin low voltage splicers. The pin connectors had already been soldered onto the driver.

I tested the motors and encoders using the test_motors utility from the GitHub repository. This utility spins the motors forward and backward alternately every 10 seconds and displays their linear velocity, angular velocity, and distance to full stop. I calibrated the rpm reading with a digital tachometer and adjusted the COUNTS_PER_REV for encoders 1-4. To run the commands, I connected the Raspberry Pi’s USB 3.1 port to the USB-C port on the general driver board and used the terminal window.

The motor setup required a lot of rewiring and learning about encoders. I learned about general wiring principles and testing the robot through the terminal on the Raspberry Pi. One encoder is not working due to improper wiring issues, but I plan to fix it after further testing.

Wednesday:

Juneteenth - No Institute

Thursday:

We had a field trip to NASA, which was very insightful. 

Friday:

Today, I focused on fixing the wiring issue for one of the encoders to ensure functionality on both wheels of the robot. After resolving the wiring issue, I proceeded with testing other sensors, connecting the Lidar, bringing up the robot, and driving it with a keyboard.

Accomplishments:

	•	Successfully installed ROS2 on a virtual machine running Ubuntu 22.04.
	•	Built and connected the power management system using a 2S LiPo battery bank and wired it to the general driver board.
	•	Conducted initial tests on the motors and encoders, learning essential wiring and testing techniques.

Challenges:

	•	Encountered improper wiring issues with one of the encoders, affecting its functionality. This required additional troubleshooting and rewiring to resolve.
	•	Faced a steep learning curve regarding general wiring principles and ensuring correct connections, which was time-consuming and required careful attention to detail.
	•	Spent significant time troubleshooting and debugging issues related to motor and encoder functionality, including calibrating the rpm reading and ensuring accurate speed measurements.

Results Achieved:

	•	Defined learning and project objectives for the week.
	•	Acquired foundational knowledge for SLAM implementation.
	•	Improved programming fluency in Linux and command line prompting.
	•	Progressed in software setup for the SLAM mini project.

Findings:

	•	Practical hands-on usage is crucial for mastering technical tools.
	•	Networking and learning from other projects can reveal alternative approaches.
	•	Engaging in discussions on ethics broadens understanding of AI’s societal impact.

Algorithms Used:

	•	SLAM (Simultaneous Localization and Mapping)
	•	Utilized the test_motors utility for testing motor functions, which includes algorithms for spinning motors and measuring their velocities and distances.
 

Insights:

	•	Practical experience with ROS and Ubuntu enhances understanding.
	•	Ethical implications of AI need careful consideration.
	•	Networking with professionals provides valuable insights and potential new approaches.


# MaxMSp

Creative Description:

	Exploring Digital Personas in a Shared Virtual Space
	
	This interactive project invites users to explore and express their digital personas within an immersive 3D environment. The custom-designed **TouchOSC** app interface allows each user to connect wirelessly and control their unique collection of floating particles. These particles change in speed, size, color, and movement, reflecting each user’s feelings. As the particles interact in real time, users can observe each other’s creations, gaining insight into their emotions and experiences. It’s a shared journey that transforms individual emotions into a collective visual experience.
	
Technical Description:

	Interactive 3D Particle System using Max MSP and TouchOSC
	
	This project employs **Max MSP** as the core visual engine and **TouchOSC** as a remote sensor interface, with **MQTT** facilitating wireless communication between the app and the Max patch. A custom-designed **TouchOSC** interface allows up to four users to connect and interact with their 3D particle sets, which can either float or follow random paths within the virtual environment.
	
	Through the app’s controls, users can adjust the speed, size, color, attraction force, and following speed of their particles. These real-time changes are sent wirelessly via MQTT, creating a dynamic, synchronized environment. Each user’s particles occupy the shared 3D space, enabling them to visually explore and understand the behaviors and expressions of other users.

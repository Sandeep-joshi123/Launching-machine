# Launching-machine
🚀 ESP32-Based Paper Plane Launcher 🚀

📚 Course Project (1st Semester):
As part of our first-semester course project, we aimed to combine theoretical concepts of aerodynamics with practical application. The goal was to create an interactive machine that could demonstrate basic aerodynamic principles through the fun and engaging activity of launching paper planes. 🛠️

🔧 ESP32 Controlled:
The project is powered by the ESP32 microcontroller, which acts as the brain of the system. The ESP32 communicates with a Bluetooth module, allowing us to send simple commands (ON/OFF) from a mobile device. This remote control setup makes the process more intuitive and user-friendly. 📱

💻 C Language Coding:
The entire system’s logic and functionality were implemented using C language. We wrote code to control the motor behavior, manage Bluetooth communication, and handle the signal activation and deactivation. C allowed us to optimize performance and ensure smooth execution of commands from the mobile interface. 👨‍💻💡

💡 Signal Activation (ON):
When the ON command is sent via Bluetooth, the system powers up and the green light turns on, indicating that the machine is ready to launch. This visual cue helps users know the system is active and ready for action. 💚

🔴 Signal Deactivation (OFF):
When the OFF signal is sent via Bluetooth, the system shuts down. The red light is activated, and the DC motors stop, ceasing the launch mechanism. This helps ensure the machine is safely deactivated and prevents any accidental launches. 🔴

⚙️ Motor Mechanism:
Two DC motors are placed in opposite directions, creating a thrust force that lifts and launches the paper plane. Based on a calculated torque of 0.1 Nm, we selected 1000 RPM DC motors to ensure sufficient power for launching the plane effectively. The motors spin in reverse directions to create rotational force, generating enough airspeed and lift to launch the plane into the air. 🔄

🔌 Power Requirements:
The power required for the motors was 24W. To meet this, we used a 12V, 2A adapter to provide sufficient voltage and current to power the motors and ESP32. This ensures smooth and consistent operation without any power shortages. 🔋⚡

💡 Embodied Energy:
The embodied energy of the system was approximately 5J. This is the energy required to produce and assemble the components, which includes the manufacturing of the materials and the assembly process. This value helps us understand the energy footprint involved in building and operating the machine. 🔋⚡

🔌 Circuit Soldering & PCB Design:
We used PCB (Printed Circuit Board) for the circuit design, ensuring a neat and efficient layout for all the components. Soldering was done to establish proper connections between the components on the PCB, making the system reliable and durable for repeated use. The well-organized PCB setup minimizes potential wiring issues and enhances the overall performance. 🔩⚡

🪶 Aesthetic Acrylic Prototype:
For a sleek and modern look, we designed the prototype casing using acrylic sheets. The acrylic sheets not only add to the aesthetic appeal but also provide a sturdy and lightweight structure for the machine. This design choice allows for better visibility of the internal components while keeping the machine compact and visually appealing. ✨💡

✈️ Aerodynamics in Action:
Through this project, we not only built a functional launcher but also gained a deeper understanding of aerodynamics. The rotation of the motors and the angle at which the paper plane is launched are directly linked to the concepts of thrust, drag, and lift. Observing the paper planes in flight helped us see these principles in action and gave us insights into how real-world aircraft operate. 🌬️📏

🔋 Power Supply and Efficiency:
The entire system is powered by a rechargeable battery, making it portable and easy to use in various environments. The ESP32 ensures that power consumption is efficient, allowing us to operate the launcher for extended periods without frequent recharging. 🔋

🎮 User-Friendly Interface:
The Bluetooth-controlled interface is simple yet effective. Users can easily control the machine from their smartphones, making the setup ideal for casual play and educational purposes. The app interface allows you to turn the launcher on/off and even monitor the status of the system in real-time. 📲

🔧 Customizable Launching Mechanism:
While the current design uses basic DC motors, future iterations of the project could allow for the customization of launch angles, motor speeds, and force adjustments. This could provide more control over the flight trajectory of the paper planes, adding a level of experimentation for users to explore different flight characteristics. 🛠️

✏️ Educational & Playful:
Beyond the technical aspects, this project was designed with both education and entertainment in mind. It’s an engaging way to teach students about basic physics principles like force, motion, and aerodynamics, all while providing an enjoyable hands-on experience. The simple yet powerful design also offers opportunities for further experimentation and improvements. 🎓🎉



#YOU CAN VIEW DETAILED DOCUMENTATION OF THE PROJECT IN https://github.com/Sandeep-joshi123/Launching-machine/wiki

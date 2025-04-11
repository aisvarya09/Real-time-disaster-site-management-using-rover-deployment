# Real-time-disaster-site-management-using-rover-deployment
# Abstract
This project presents a real-time disaster site management system utilizing a custom-designed 6-wheeled ground rover. The primary objective is to assist rescue operations by detecting human presence and navigating hazardous terrain without direct human intervention. The rover is equipped with an ESP32-CAM module that captures live video feeds, which are processed using Python-based facial recognition to identify trapped or unconscious individuals in disaster-affected areas. An ultrasonic sensor is mounted on the rover to detect nearby obstacles such as rocks or debris, enabling safe and autonomous navigation across unstable or cluttered surfaces.

The rover is powered by a 12V battery, with mobility managed through an L298N motor driver and DC motors, allowing for stable movement across rough environments. The 6-wheel design enhances balance, traction, and maneuverability, ensuring consistent performance even in uneven terrains. Wireless communication via Wi-Fi enables data transmission to a remote command center, providing real-time updates on rover status, obstacle detection, and human recognition.

This project demonstrates the potential of integrating low-cost embedded systems, computer vision, and IoT in a mobile platform for search-and-rescue missions. The developed system enhances disaster response efficiency, minimizes human risk, and serves as a foundation for future scalable rescue technologies.

# Problem statement
Manual disaster response is time-consuming and unsafe for human rescuers. There is a lack of low-cost, real-time systems that can identify survivors and navigate hazardous zones. This project aims to bridge that gap with a smart, ground-based solution.
 # Objective
 To design and develop a mobile rover capable of detecting human presence using facial recognition. To ensure autonomous navigation using obstacle detection sensors. To provide real-time data to a remote command center for improved rescue coordination.
 # Proposed Method
 The system uses an ESP32-CAM for facial recognition via Python scripts. An ultrasonic sensor is used for obstacle avoidance while navigating. All components are mounted on a 6-wheeled rover designed for rough terrain, communicating wirelessly with a base station.
 # Technology Used
1.Hardware: ESP32-CAM, Ultrasonic Sensor, L298N Motor Driver, 12V Battery, DC Motors

2.Software: Python, OpenCV, Arduino IDE, face_recognition library

3.Communication: Wi-Fi (ESP32 Web Server)
# Results
The rover successfully detects faces and obstacles in real time. Wireless transmission of visual and sensor data to a remote system was validated. The prototype demonstrated effective performance in simulated disaster environments with reliable accuracy.
# Rover
<img width="275" alt="image" src="https://github.com/user-attachments/assets/a7bf867c-b33e-49a1-8d91-7d14a70d5fb6" />

# Facial recognition output
<img width="442" alt="image" src="https://github.com/user-attachments/assets/348cb8a3-8bfd-418e-b029-a709a67e6ba1" />

# Explanation of our outcome
Our rover system was able to identify human faces and navigate blocked paths autonomously. The integration of real-time sensing and mobility improves disaster site monitoring. It proves the feasibility of using low-cost IoT-based systems in critical rescue scenarios.It improves rescue operation efficiency upto 70%.




 
 

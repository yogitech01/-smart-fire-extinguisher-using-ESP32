# -smart-fire-extinguisher-using-ESP32
This project focuses on the development of a Fire Extinguisher Robot, an autonomous robotic system capable of detecting and extinguishing fires without human involvement. The robot is designed to monitor its environment . Upon detecting a fire, it activates a mobility mechanism such as wheels or tracks to navigate toward the fire source.
# 🔥 Fire Extinguisher Robot

An **IoT-based Fire Extinguisher Robot** designed to detect, monitor, and extinguish fires autonomously using embedded systems, sensors, and wireless communication. The robot continuously monitors its surroundings for fire, smoke, and abnormal temperature conditions, navigates toward the fire source while avoiding obstacles, and activates a fire suppression mechanism. It also provides real-time monitoring and notifications through a smartphone application.

---

# 📖 Project Overview

Fire accidents pose a major threat to human lives, property, and industrial infrastructure. Traditional fire-fighting methods often require human intervention, which can expose firefighters to dangerous environments and delay emergency response.

The **Fire Extinguisher Robot** addresses these challenges by providing an autonomous robotic solution capable of:

* Detecting fire using multiple sensors.
* Moving toward the fire source automatically.
* Avoiding obstacles during navigation.
* Activating a fire extinguishing mechanism.
* Sending real-time alerts and sensor data to a smartphone.
* Logging sensor readings and fire events through cloud services.

The project integrates **Embedded Systems**, **Internet of Things (IoT)**, **Wireless Communication**, and **Cloud Technology** to improve fire safety and emergency response.

---

# 🎯 Objectives

* Develop an autonomous fire detection system.
* Detect flames, smoke, gas leakage, and abnormal temperature.
* Navigate safely using obstacle avoidance.
* Automatically extinguish detected fires.
* Provide real-time monitoring through a mobile application.
* Send emergency notifications to users.
* Store fire event data for future analysis.
* Minimize human intervention during fire emergencies.

---

# ✨ Features

## 🔥 Fire Detection

* Real-time flame detection.
* Smoke and combustible gas monitoring.
* Temperature monitoring.
* Continuous environmental scanning.

## 🤖 Autonomous Navigation

* Automatic movement toward fire.
* Obstacle detection using ultrasonic sensors.
* Intelligent path correction.

## 🚒 Fire Extinguishing

* Automatic activation of water pump or CO₂ extinguisher.
* Relay-controlled suppression system.
* Immediate response after fire detection.

## 📱 Smartphone Monitoring

* Live sensor readings.
* Fire detection notifications.
* Robot status monitoring.
* Manual robot control.
* Fire suppression control.

## ☁ Cloud Integration

* Firebase Realtime Database.
* Event logging.
* Sensor history.
* Remote access.

---

# 🛠 Hardware Components

* Arduino Uno / Raspberry Pi
* L298N Motor Driver
* Flame Sensor
* MQ-2 Gas Sensor
* Temperature Sensor (LM35 / DHT11)
* Ultrasonic Sensor (HC-SR04)
* DC Motors
* Robot Chassis
* Relay Module
* Mini Water Pump / CO₂ Extinguisher
* Rechargeable Battery Pack
* LED Indicators
* Buzzer
* Jumper Wires
* Breadboard

---

# 💻 Software Requirements

### Operating System

* Windows
* Linux
* Raspberry Pi OS

### Programming Languages

* Embedded C
* C++
* Python
* Dart
* JavaScript

### IDE

* Arduino IDE
* Visual Studio Code
* Thonny
* PyCharm

### Mobile Development

* Flutter
* Dart

### Cloud Services

* Firebase Realtime Database
* Firebase Authentication

---

# ⚙ System Architecture

The Fire Extinguisher Robot consists of several interconnected modules working together to perform autonomous fire detection and suppression.

1. Flame, gas, and temperature sensors continuously monitor the surroundings.
2. The microcontroller processes sensor data.
3. When fire is detected, the robot identifies the fire location.
4. The ultrasonic sensor detects obstacles.
5. The motor driver controls the robot movement.
6. The robot approaches the fire source.
7. The relay activates the extinguisher mechanism.
8. Sensor data is uploaded to Firebase.
9. Users receive real-time alerts on their smartphone.
10. Fire event information is stored for future analysis.

---

# 🔄 Working Principle

1. Power is supplied to the robot.
2. Sensors continuously scan the environment.
3. Flame sensor detects fire.
4. Gas sensor detects smoke or combustible gases.
5. Temperature sensor monitors heat levels.
6. Ultrasonic sensor prevents collisions.
7. Arduino/Raspberry Pi processes the sensor inputs.
8. Robot automatically moves toward the detected fire.
9. Relay activates the water pump or CO₂ extinguisher.
10. Firebase stores sensor values and event logs.
11. Smartphone application displays live data and sends emergency notifications.
12. User can manually control the robot if required.

---

# 📱 Mobile Application Features

* Live Fire Detection Status
* Temperature Monitoring
* Gas Concentration Monitoring
* Robot Movement Status
* Fire Alert Notifications
* Manual Robot Controls
* Fire Extinguisher Control
* Event History
* Cloud Synchronization
* User Authentication

---

# ☁ Firebase Integration

The project uses Firebase for cloud communication.

Features include:

* Realtime Database
* Authentication
* Sensor Data Storage
* Fire Event Logging
* Smartphone Synchronization
* Notification Support

---

# 📂 Suggested Repository Structure

```
Fire-Extinguisher-Robot/
│
├── Arduino_Code/
│   ├── fire_robot.ino
│
├── RaspberryPi/
│   ├── main.py
│
├── Mobile_App/
│   ├── Flutter/
│
├── Firebase/
│   ├── firebase_config.json
│
├── Circuit_Diagram/
│   ├── circuit.png
│
├── Block_Diagram/
│   ├── block_diagram.png
│
├── Images/
│   ├── robot_front.jpg
│   ├── robot_side.jpg
│   ├── app_dashboard.png
│
├── Documentation/
│   ├── Project_Report.pdf
│   ├── Presentation.pdf
│
├── README.md
└── LICENSE
```

---

# 🚀 Future Enhancements

* AI-based fire prediction.
* Thermal camera integration.
* Computer vision for fire localization.
* GPS-based outdoor navigation.
* Voice-controlled robot.
* Solar-powered charging.
* Integration with smart building systems.
* Multiple robot coordination.
* Automatic emergency service notification.
* Machine Learning for false alarm reduction.

---

# 🎓 Applications

* Industrial Plants
* Warehouses
* Chemical Laboratories
* Schools and Colleges
* Hospitals
* Shopping Malls
* Data Centers
* Office Buildings
* Residential Apartments
* Smart Homes

---

# 📈 Advantages

* Rapid fire detection.
* Autonomous operation.
* Reduced human risk.
* Real-time monitoring.
* Remote accessibility.
* Cloud-based data storage.
* Cost-effective solution.
* Easy maintenance.
* Expandable architecture.
* Improved emergency response.

---

# 📊 Technologies Used

| Category        | Technology                          |
| --------------- | ----------------------------------- |
| Microcontroller | Arduino Uno / Raspberry Pi          |
| Programming     | Embedded C, C++, Python             |
| IoT             | Firebase                            |
| Mobile App      | Flutter, Dart                       |
| Sensors         | Flame, MQ-2, DHT11/LM35, Ultrasonic |
| Communication   | Wi-Fi / Bluetooth                   |
| Database        | Firebase Realtime Database          |

---

# 📸 Project Demonstration

Include the following images in your repository:

* Robot Front View
* Robot Side View
* Circuit Diagram
* Block Diagram
* Hardware Connections
* Sensor Setup
* Mobile Application Dashboard
* Fire Detection Demonstration
* Fire Extinguishing Demonstration

---


# 📜 License

This project is developed for educational and research purposes. You are free to use, modify, and improve it with proper attribution.

---

## ⭐ If you found this project useful, don't forget to **Star ⭐ the repository** and contribute with ideas or improvements!

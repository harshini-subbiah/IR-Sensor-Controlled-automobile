# 🚗 IR Sensor Controlled Autonomous Automobile

An **8051 microcontroller-based autonomous robot** that uses **Infrared (IR) sensors** to detect obstacles and navigate its surroundings without human intervention. The robot continuously monitors its environment and responds in real time by controlling its motors and activating a buzzer whenever an obstacle is detected.

---

## 📖 Overview

This project demonstrates the implementation of an autonomous vehicle using the **AT89S52 (8051) microcontroller**. Three IR sensors are used to detect obstacles, while an **L293D motor driver** controls the movement of two DC motors. A buzzer provides audible alerts whenever an obstacle is encountered.

The project serves as a practical introduction to:
- Embedded Systems
- 8051 Microcontroller Programming
- IR Sensor Interfacing
- Motor Driver Control
- Obstacle Detection and Avoidance

---

## ✨ Features

- 🚗 Autonomous navigation
- 📡 Real-time obstacle detection using IR sensors
- 🔄 Automatic movement control
- 🔊 Buzzer alert on obstacle detection
- ⚙️ 8051 Assembly language implementation
- 💡 Simple and low-cost hardware design

---

## 🛠️ Hardware Components

| Component | Quantity |
|-----------|---------:|
| AT89S52 Microcontroller | 1 |
| L293D Motor Driver IC | 1 |
| TSOP18638 IR Sensors | 3 |
| DC Motors | 2 |
| BC547 NPN Transistor | 1 |
| Resistor | 1 |
| Buzzer | 1 |
| 5V Power Supply | 1 |
| Breadboard | 1 |
| Connecting Wires | As Required |

---

## 💻 Software Requirements

- **Keil uVision** (for writing and compiling the Assembly code)
- **8051 ISP Programmer**
- USBASP Driver

### Installation Guide

Follow this guide to install the programmer and drivers:

https://www.instructables.com/USBASP-Installation-in-Windows-10/

---

---

## ⚡ Getting Started

### 1. Assemble the Hardware

Connect all the components according to the provided circuit diagram.

### 2. Compile the Program

Open **Code.asm** in **Keil uVision** and build the project to generate the HEX file.

### 3. Program the Microcontroller

Use the **8051 ISP Programmer** to upload the generated HEX file to the **AT89S52** microcontroller.

### 4. Power the Circuit

Provide a regulated **5V power supply** and place the robot on a flat surface.

### 5. Run

The robot will:
- Detect obstacles using the IR sensors.
- Move autonomously based on sensor inputs.
- Activate the buzzer whenever an obstacle is detected.

---

## ⚙️ Working Principle

1. The IR sensors continuously monitor the area in front of the robot.
2. Sensor signals are sent to the AT89S52 microcontroller.
3. The microcontroller processes the sensor inputs.
4. Based on the detected obstacle, the controller drives the motors through the L293D motor driver.
5. A buzzer is activated to indicate obstacle detection.

---

## 📸 Project Preview

<img width="828" height="645" alt="image" src="https://github.com/user-attachments/assets/18f9d8dd-d0d2-4fac-93bd-9257852c5d2f" />




## 🚀 Future Improvements

- Ultrasonic sensor integration
- Bluetooth/Wi-Fi control
- Line-following mode
- PID-based navigation
- Rechargeable battery management
- Obstacle distance estimation

---

## 👩‍💻 Author

**Harshini Subbiah**

Embedded Systems | Electronics | Robotics

## Contributors

Akshaya H

Subiksha 

---

## 📄 License

This project is intended for educational and learning purposes.

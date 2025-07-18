# 5 DOF Smart Robotic Arm

This is a low-cost, 3D-printed, 5 Degrees of Freedom robotic arm using Dynamixel AX-12A smart servos.
It features inverse kinematics control, Arduino firmware, and a Python-based GUI for controlling the arm.

## Features
- 5 DOF articulated arm
- 3D-printable design (STL and STEP files included)
- Dynamixel smart servos
- Python-based inverse kinematics (IK) control interface
- Arduino firmware for controlling servo communication
- Modular and educational design

## Components
### Mechanical:
- STL and STEP files provided
- Modular joint design
- Lightweight and customizable

### Electrical:
- Dynamixel AX-12A Servos
- Arduino Mega (or compatible)
- 12V Power Supply

### Software:
- Python 3 scripts (IK + GUI)
- Arduino firmware
- Optional ROS integration (experimental)

## Getting Started

### Prerequisites
- Python 3
- Arduino IDE
- Python libraries: pyserial, numpy

### Installation
1. Clone the repository:
   git clone https://github.com/DhruvaRaoAS/SMART-ARM.git

2. Upload `firmware/servo_control.ino` to Arduino.

3. Run the Python IK control interface:
   python python/ik_control.py

## Control Methods
- Manual joint control (via GUI sliders)
- Inverse Kinematics: move the end-effector to desired coordinates
- Record and playback sequences

## File Structure
- `/cad` - STL and STEP files
- `/firmware` - Arduino code
- `/python` - Python GUI and IK scripts
- `/docs` - Assembly instructions, schematics

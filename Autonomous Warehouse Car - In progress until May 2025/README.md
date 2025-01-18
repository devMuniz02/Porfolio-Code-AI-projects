# Autonomous Warehouse Car

## Overview
This repository documents the development and implementation of an autonomous warehouse car using the Hiwonder TurboPi Raspberry Pi 4B Omnidirectional Mecanum Wheels Robot Car Kit with Camera. The project aims to demonstrate the car's ability to navigate autonomously within a warehouse environment, leveraging its open-source capabilities and advanced features.

![Hiwonder TurboPi Robot Car](https://www.hiwonder.com/cdn/shop/products/1_6e85e9c0-9159-4cbf-a56e-1bfedd29c624.jpg?v=1675655593)

You can purchase the robot car [here](https://www.hiwonder.com/products/turbopi?variant=40112905388119&srsltid=AfmBOopmSs3-KjVfpT4d8Sjfc3YMwAOfS9M41YovacwbGjmsZ1QDkVyq).

---

## Features

### 1. Mecanum Wheels for Omnidirectional Movement
- Smooth navigation in any direction.
- Ideal for tight spaces and complex warehouse layouts.

### 2. Camera Integration
- Enables visual feedback for object recognition and navigation.
- Supports advanced vision-based tasks, such as barcode or QR code scanning.

### 3. Raspberry Pi 4B
- Provides powerful computing capabilities for real-time decision-making.
- Open-source platform for custom software development.

### 4. Expandability
- Open-source design allows for easy integration of additional sensors and hardware.

---

## Folder Structure

### 1. LiDAR2D
Contains resources and code for integrating and using a 2D LiDAR sensor for precise mapping and obstacle detection.

### 2. Line Follower
Includes scripts and configurations for enabling line-following behavior in the robot car.

### 3. Location
Documentation and code for localization and position tracking within the warehouse environment.

### 4. QR Reader
Resources for integrating QR code reading functionality using the onboard camera.

### 5. Ultrasonic
Code and setup for ultrasonic sensors to assist with obstacle detection and distance measurement.

### 6. UR3e Universal Robots
Details about collaborative applications involving the UR3e robot arm.

---

## Project Goals
1. Implement autonomous navigation within a simulated warehouse environment.
2. Develop obstacle detection and avoidance algorithms.
3. Incorporate camera-based tasks such as item recognition and sorting.
4. Test and refine navigation and task execution efficiency.

---

## Prerequisites
- **Hardware**:
  - Hiwonder TurboPi Robot Car Kit with Camera
  - Raspberry Pi-compatible power supply
  - Additional sensors (optional)
- **Software**:
  - Python 3.x
  - OpenCV for computer vision tasks
  - RPi.GPIO for GPIO control
  - Custom navigation and control scripts

---

## Getting Started
This section provides step-by-step guidance for setting up the autonomous warehouse car. Detailed photos and videos of the process will be included once completed.

1. **Assembly**:
   - Follow the assembly instructions provided with the TurboPi kit.
   - Ensure all components are securely attached.

2. **Software Setup**:
   - Install the Raspberry Pi OS and required libraries (e.g., OpenCV, RPi.GPIO).
   - Clone this repository and upload scripts to the Raspberry Pi.

3. **Initial Tests**:
   - Calibrate the mecanum wheels for smooth movement.
   - Test camera integration and basic navigation.

---

## Work in Progress
Currently, this project is under active development. Photos, videos, and additional documentation demonstrating the car's assembly and functionality will be added soon.

Planned updates include:
- Detailed setup guides with visuals.
- Demonstration videos for navigation, obstacle avoidance, and camera-based tasks.
- Performance metrics and troubleshooting tips.


# Using CAN Protocol for Quadcopter – A Model-Based Design Approach

This project demonstrates the implementation of the **Controller Area Network (CAN)** protocol in a **quadcopter flight control system** using **MATLAB Simulink**. The goal is to simulate real-time communication between sensors and controllers, implement stable control using **PID algorithms**, and verify performance through simulation before hardware deployment.

## Table of Contents
- [Project Overview](#project-overview)
- [System Architecture](#system-architecture)
- [Key Features](#key-features)
- [Software Requirements](#software-requirements)
- [Getting Started](#getting-started)
- [Simulation Snapshots](#simulation-snapshots)
- [Acknowledgements](#acknowledgements)

---

## Project Overview

The quadcopter model includes:
- **IMU Sensor Simulation**: Provides attitude and motion feedback
- **PID Control System**: Stabilizes roll, pitch, and yaw axes
- **CAN Communication Protocol**: Ensures deterministic data transfer between simulated subsystems

Model-Based Design (MBD) enables system-level simulation and validation prior to real-world testing.

---

## System Architecture

- Simulink-based model with modular subsystems:
  - IMU Sensor (input)
  - CAN Transmitter/Receiver blocks
  - PID Controllers
  - Quadcopter Dynamics
- Real-time communication modeled using **Simulink CAN Communication Blocks**
- Feedback loop structure for closed-loop performance analysis

---

## Key Features

- Implementation of **CAN protocol** for embedded UAV communication  
- **PID controller tuning** for stable quadcopter control  
- Real-time data exchange and system validation using simulation  
- Scalable model suitable for future hardware-in-the-loop (HIL) testing  

---

## Software Requirements

- MATLAB R2024b or later  
- Simulink  
- Simulink Coder (for code generation – optional)  
- Vehicle Dynamics Blockset (for UAV modeling – optional)  
- Embedded Coder (for CAN protocol – optional)  

---

##Simulation-Snapshots
![image](https://github.com/user-attachments/assets/1af38abd-5a43-4bc2-a351-681155ea9d77)
![can](https://github.com/user-attachments/assets/91013228-edf0-4b25-848b-aab7897eabeb)
![flight_controller](https://github.com/user-attachments/assets/3f629b56-ae87-4e0d-bc93-a8f66d9e5033)
![imu](https://github.com/user-attachments/assets/5b5d3418-34e1-4784-83a4-7dde07e38fc3)




1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/quad-copter-can-simulink.git

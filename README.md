﻿# Real-Time Robot Arm Simulator 🤖

## Description
The simulator will be developed using **Blender** for 3D modeling, rigging, and simulation, alongside **Python** or **Rust** scripting for communication and synchronization with the physical robot. The main goal is to provide a virtual representation that mirrors the real-world robotic arm's behavior, enabling users to visualize and control it through the simulator interface.

## Project Overview

### Steps Involved:
1. **3D Modeling**: Create a detailed 3D model of the robotic arm and its components in Blender, based on the KUKA KR 700 PA.
2. **Rigging**: Rig the robot arm in Blender, with a control system corresponding to the real robot’s joints and actuators.
3. **Scripting**: Develop Python or Rust scripts to communicate with the Atmega or STM controller, enabling real-time synchronization.
4. **Real-time Simulation**: Implement a real-time simulator that continuously updates its behavior based on sensor data from the real robot.
5. **User Interface**: Design an interactive UI in Blender to control the robotic arm, send commands, and visualize sensor data.
6. **Documentation and Tutorials**: Provide thorough documentation and tutorials on setting up the project, hardware, and software.

## Unique Aspects
This project stands out in the following ways:
- **Target Audience**: Tailored for students and educators, it focuses on simplicity and accessibility.
- **Hardware Compatibility**: Designed to work with NEMA stepper motors, motor drivers, and Atmega/STM controllers.
- **KUKA KR 700 PA Inspiration**: Provides a practical, industry-standard learning experience.
- **Blender Integration**: Leverages Blender’s powerful features for 3D modeling and simulation.
- **Customizability**: Fully open-source, encouraging community contributions, modifications, and innovation.

## Starter Project: 2R Pick and Place Robot Arm Simulation
The simulation involves a 2-link robotic arm performing pick-and-place tasks, covering:

- Forward and Inverse Kinematics
- Robot Arm Geometry
- Quaternions in Robotics
- Animation and Visualization
- Pick and Place Task
- Trajectory Planning
- Error Handling and Limits

The simulation uses **matplotlib** for visualization and **numpy** for calculations. It simulates the pick-and-place process, visualizing the robot’s movements in real-time.

## Robot arm pick and place simulation
![Robot Arm Simulation](https://github.com/s-naveenkumar-001/Robotics-Projects/blob/main/documents/Robot_arm_simulation.gif)

## Practical Applications
- Educational tool for students learning about robotics.
- Testbed for developing and refining robotic control algorithms.
- A resource for testing hardware compatibility and synchronization between virtual and real-world robots.

## Getting Started
1. **Clone the Repository**: Download the project files and ensure you have **Blender** installed.
2. **Install Dependencies**: Install necessary Python or Rust libraries and ensure Blender is set up with the required add-ons.
3. **Hardware Setup**: Connect your physical robotic arm (using NEMA stepper motors, motor drivers, and Atmega/STM controllers).
4. **Run the Simulation**: Launch the Blender simulator, interface it with the physical hardware, and start exploring!

## License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

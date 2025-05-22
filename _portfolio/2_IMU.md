---
title: "Modelling and Simulation of a Strapped-Down Inertial Measuring Unit (IMU)"
excerpt: "Developing a SIMULINK model to simulate the navigation equations of a strapped-down IMU and assess flight vehicle navigation principles. <br/><img src='/images/InnerSys.png' width='300'>"
collection: portfolio
---

**Module Title**: Advanced Flight Control and Simulation of Aerospace Vehicles | **Location**: London, UK | **Dates**: Oct 2024 - Current

This project, part of the EMS 716 Advanced Flight Control and Simulation of Aerospace Vehicles coursework, focuses on the Modelling and Simulation of a Strapped-Down Inertial Measuring Unit (IMU). The primary learning objective is to familiarize students with the navigation principles of a flight vehicle and assess the performance of an IMU-based navigation system. By simulating both the navigation and error dynamics equations, I aim to evaluate how errors propagate through the system and impact the accuracy of flight navigation.

### Project Overview:
- **Navigation Equations Simulation**: I have developed a SIMULINK model to simulate the navigation equations for a strapped-down IMU. This simulation replicates how a vehicle’s position, velocity, and attitude are calculated based on sensor data in a real-world system. The use of **Euler angles** transforms angular velocities into attitude rates, which helps understand the orientation of the flight vehicle.
  
- **Error Dynamics Simulation**: The IMU is prone to accumulating errors over time, such as sensor biases and noise. To address this, I have implemented error dynamics within the SIMULINK model. This simulation examines how these errors evolve and propagate, helping me predict how they affect navigation accuracy. Understanding these error behaviours is critical for improving IMU-based systems in real-world applications.

- **Interface Design and Validation**: I have also built interfaces within the SIMULINK environment to display the results in a user-friendly format. This includes visualizing navigation data, error accumulation, and flight dynamics. Validation tests are being conducted to compare the simulation results against theoretical expectations, ensuring that the model behaves as anticipated.

- **Simulation Limitations and Future Work**: The current model uses Euler angles for transformations, which presents singularities at certain orientations (e.g., at 90 degrees, cos(θ) becomes zero). To overcome this, I plan to explore the implementation of quaternions to improve stability and avoid singularities in the attitude transformation process.

- **Report Deliverables**: The project will culminate in a detailed report that includes background theory, simulation methodology, block diagrams, results analysis, and an exploration of potential flight control or navigation modes. The report will also discuss practical limitations, achievements, and future improvements to the IMU simulation. 

### Learning Outcomes:
This project enhances my understanding of flight navigation principles and system dynamics while allowing me to delve into error prediction techniques in IMU systems. Additionally, I have gained hands-on experience in MATLAB/SIMULINK, which is instrumental for aerospace control systems.

A Full system diagram can be seen in Figure 1 below.

**Figure 1**: Internal IMU Simulink diagram. 
![Inner Simulink Diagram](/images/InnerSys.png)

**Key Skills Developed:**
- **Technical Skills**: Inertial Navigation, SIMULINK, Error Prediction, System Modelling, Flight Dynamics, Quaternion Implementation.
- **Soft Skills**: Analytical Thinking, Report Writing, Problem Solving, Presentation.

<!-- [Full Report (PDF)](https://Joosty.github.io/files/IMU_Simulator_Report.pdf) -->

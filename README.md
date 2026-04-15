# Satellite Orbit Control

This project focuses on the analysis and control of a satellite orbit system. The objective is to study the dynamic behavior of the satellite and design a controller capable of driving the system toward a desired operating condition while satisfying given performance requirements such as tracking accuracy, response time, and limited oscillations. :contentReference[oaicite:0]{index=0}

## Project Overview

The system under analysis is a satellite orbiting the Earth, equipped with actuators that generate both tangential propulsion and control torque. The project studies how to regulate the satellite dynamics in order to achieve a desired orbital condition through mathematical modeling, control analysis, and simulation. :contentReference[oaicite:1]{index=1}

The work combines theoretical control methods with simulation-based validation. Starting from the nonlinear equations of motion, the project develops a linearized model, derives the transfer function, analyzes stability, designs a controller, and verifies the results through MATLAB and Simulink simulations. :contentReference[oaicite:2]{index=2} :contentReference[oaicite:3]{index=3}

## Main Objectives

- model the satellite dynamics starting from the given physical equations
- determine the equilibrium configurations of the system
- linearize the nonlinear model around the equilibrium point
- analyze the free evolution and stability of the system
- derive the transfer function and study poles and zeros
- design a controller that satisfies the required static and dynamic specifications 
- validate the controller through simulations on both linearized and nonlinear models.
## Mathematical and Engineering Tools Used

This project applies several mathematical and control-engineering concepts, including:

- **nonlinear dynamical system modeling** based on physical equations
- **equilibrium analysis** to identify steady-state operating conditions
- **linearization** of the nonlinear model for control-oriented analysis
- **state-space representation** using state and input vectors
- **eigenvalue analysis** and **Jordan form** for free response and stability discussion
- **Laplace transform** and **transfer function derivation**
- **pole-zero analysis** and stability interpretation
- **Bode analysis** for frequency-domain reasoning
- **controller design** based on static and dynamic performance specifications
- **simulation-based validation** on both approximate and nonlinear models
## Software and Tools

The project was developed using:

- **MATLAB** for analytical support and controller design
- **Simulink** for system simulation and validation
- **SISOTOOL** for interactive controller tuning and frequency-domain design
  
## Control Design Approach

The project follows a standard control-system workflow:

1. formulation of the nonlinear model
2. computation of equilibrium conditions
3. derivation of a linearized state-space model
4. stability and modal analysis
5. derivation of the transfer function
6. controller design according to tracking and timing requirements
7. validation through simulations of both the linear and nonlinear system

## What This Project Demonstrates

This project highlights skills in:

- mathematical modeling of physical systems
- analytical reasoning for dynamical systems
- control-system analysis and controller design
- simulation-driven validation
- technical documentation and structured problem solving
- teamwork in a multi-member engineering project

## Notes

The final simulations show that the nonlinear model behaves significantly differently from the linearized approximation, leading to the conclusion that the system is not well suited to linearization in that operating context. This makes the project particularly useful as an example of critical evaluation of model assumptions and limitations

# Satellite Orbit Control

This project focuses on the analysis and control of a satellite orbit system. The objective is to study the dynamic behavior of the satellite and design a controller capable of driving the system toward a desired operating condition while satisfying given performance requirements such as tracking accuracy, response time, and limited oscillations. :contentReference[oaicite:0]{index=0}

## Project Overview

The system under analysis is a satellite orbiting the Earth, equipped with actuators that generate both tangential propulsion and control torque. The project studies how to regulate the satellite dynamics in order to achieve a desired orbital condition through mathematical modeling, control analysis, and simulation. :contentReference[oaicite:1]{index=1}

The work combines theoretical control methods with simulation-based validation. Starting from the nonlinear equations of motion, the project develops a linearized model, derives the transfer function, analyzes stability, designs a controller, and verifies the results through MATLAB and Simulink simulations. :contentReference[oaicite:2]{index=2} :contentReference[oaicite:3]{index=3}

## Main Objectives

- model the satellite dynamics starting from the given physical equations; :contentReference[oaicite:4]{index=4}
- determine the equilibrium configurations of the system; :contentReference[oaicite:5]{index=5}
- linearize the nonlinear model around the equilibrium point; :contentReference[oaicite:6]{index=6}
- analyze the free evolution and stability of the system; :contentReference[oaicite:7]{index=7}
- derive the transfer function and study poles and zeros; :contentReference[oaicite:8]{index=8}
- design a controller that satisfies the required static and dynamic specifications; :contentReference[oaicite:9]{index=9}
- validate the controller through simulations on both linearized and nonlinear models. :contentReference[oaicite:10]{index=10}

## Mathematical and Engineering Tools Used

This project applies several mathematical and control-engineering concepts, including:

- **nonlinear dynamical system modeling** based on physical equations; :contentReference[oaicite:11]{index=11}
- **equilibrium analysis** to identify steady-state operating conditions; :contentReference[oaicite:12]{index=12}
- **linearization** of the nonlinear model for control-oriented analysis; :contentReference[oaicite:13]{index=13}
- **state-space representation** using state and input vectors; :contentReference[oaicite:14]{index=14}
- **eigenvalue analysis** and **Jordan form** for free response and stability discussion; :contentReference[oaicite:15]{index=15}
- **Laplace transform** and **transfer function derivation**; :contentReference[oaicite:16]{index=16}
- **pole-zero analysis** and stability interpretation; :contentReference[oaicite:17]{index=17}
- **Bode analysis** for frequency-domain reasoning; :contentReference[oaicite:18]{index=18}
- **controller design** based on static and dynamic performance specifications; :contentReference[oaicite:19]{index=19}
- **simulation-based validation** on both approximate and nonlinear models. :contentReference[oaicite:20]{index=20}

## Software and Tools

The project was developed using:

- **MATLAB** for analytical support and controller design; :contentReference[oaicite:21]{index=21}
- **Simulink** for system simulation and validation; :contentReference[oaicite:22]{index=22}
- **SISOTOOL** for interactive controller tuning and frequency-domain design. :contentReference[oaicite:23]{index=23}

## Control Design Approach

The project follows a standard control-system workflow:

1. formulation of the nonlinear model; :contentReference[oaicite:24]{index=24}
2. computation of equilibrium conditions; :contentReference[oaicite:25]{index=25}
3. derivation of a linearized state-space model; :contentReference[oaicite:26]{index=26}
4. stability and modal analysis; :contentReference[oaicite:27]{index=27}
5. derivation of the transfer function; :contentReference[oaicite:28]{index=28}
6. controller design according to tracking and timing requirements; :contentReference[oaicite:29]{index=29}
7. validation through simulations of both the linear and nonlinear system. :contentReference[oaicite:30]{index=30}

## What This Project Demonstrates

This project highlights skills in:

- mathematical modeling of physical systems;
- analytical reasoning for dynamical systems;
- control-system analysis and controller design;
- simulation-driven validation;
- technical documentation and structured problem solving;
- teamwork in a multi-member engineering project. :contentReference[oaicite:31]{index=31}

## Notes

The final simulations show that the nonlinear model behaves significantly differently from the linearized approximation, leading to the conclusion that the system is not well suited to linearization in that operating context. This makes the project particularly useful as an example of critical evaluation of model assumptions and limitations. :contentReference[oaicite:32]{index=32}

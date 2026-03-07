---
title: "QUPA Distributed Robotic Platform"
collection: portfolio
permalink: /portfolio/qupa
---

QUPA is a modular robotic platform developed for experimentation with distributed robotic systems and cooperative behaviors. The project integrates mechanical design, embedded systems, perception, and multi-robot simulation to study how resource-constrained robots can coordinate to perform collective tasks.

The platform was designed to explore decentralized perception, local decision-making, and swarm-level behaviors through both simulation and real-world experiments.

---

## Physical Robotic Platform

The QUPA robot is a compact mobile robot equipped with an embedded controller, onboard sensing, and a modular manipulation system. The robot was designed to manipulate small objects while operating as part of a cooperative robotic group.

<p align="center">
<img src="/images/qupa_Real.jpeg" width="450">
</p>

Key characteristics of the platform include:

- ESP32-based embedded control system  
- Modular mechanical architecture  
- Low-cost and resource-constrained design  
- Onboard perception for object detection  
- Manipulation module for cooperative tasks  

---

## Multi-Robot Simulation

To study collective robotic behaviors, the system was modeled and simulated using ARGoS and Gazebo. These environments allow testing swarm coordination strategies and analyzing how task performance changes as the number of robots increases.

<p align="center">
<img src="/images/qupa_argos_simulation.png" width="600">
</p>

Simulation experiments evaluated:

- task completion time  
- cooperation efficiency  
- scaling behavior as more robots participate  

These experiments provide insight into how decentralized coordination strategies affect swarm performance.

---

## Perception and Sim-to-Real Validation

The robots use onboard camera perception to detect objects and decide how to interact with them. A color-based detection pipeline allows the robot to identify targets and determine navigation direction.

<p align="center">
<img src="/images/qupa_perception_comparison.png" width="650">
</p>

The perception pipeline includes:

- HSV color segmentation  
- contour detection and filtering  
- centroid estimation for navigation decisions  

Comparing simulated perception with real camera data allows validation of the simulation models and helps bridge the gap between simulation and physical experiments.

---

## System Architecture

The QUPA platform integrates mechanical, electronic, and embedded subsystems in a compact architecture.

<p align="center">
<img src="/images/qupa_internal_architecture.png" width="600">
</p>

The system combines:

- embedded computation  
- motor control and actuation  
- onboard perception  
- communication between modules  

This architecture enables experimentation with decentralized robotic behaviors in both simulation and real environments.

---

## Experimental Results

Experiments were conducted using one to three robots performing cooperative object collection tasks. Results showed that increasing the number of robots significantly reduced the average task completion time while maintaining high efficiency.

These experiments demonstrate how simple local rules can produce cooperative behaviors in groups of robots.

---

## Research Direction

The QUPA platform provides a foundation for research in:

- swarm robotics  
- distributed autonomous systems  
- decentralized control strategies  
- simulation-to-real robotic validation  

The system continues to serve as a testbed for exploring how small autonomous robots can cooperate to perform complex tasks.

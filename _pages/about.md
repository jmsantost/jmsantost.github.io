---
permalink: /
title: "About Me"
excerpt: "Autonomous Robotics, Distributed Systems, and Swarm Robotics"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div class="hero">
<p class="hero__title">Mechatronics Engineer · Autonomous Robotics &amp; Control</p>
<p class="hero__tagline">Multi-robot systems, navigation and control (MPC, MPPI) with ROS / ROS 2, Gazebo and ARGoS, validated on real robotic platforms.</p>
<p class="hero__actions">
<a class="hero__btn hero__btn--primary" href="/cv/"><i class="fas fa-file" aria-hidden="true"></i> CV</a>
<a class="hero__btn" href="https://github.com/jmsantost"><i class="fab fa-github" aria-hidden="true"></i> GitHub</a>
<a class="hero__btn" href="https://www.linkedin.com/in/jmsantost"><i class="fab fa-linkedin" aria-hidden="true"></i> LinkedIn</a>
<a class="hero__btn" href="https://scholar.google.com/citations?view_op=list_works&amp;hl=es&amp;user=zb1Dd6IAAAAJ"><i class="fas fa-graduation-cap" aria-hidden="true"></i> Scholar</a>
<a class="hero__btn" href="mailto:josemiguelsantost@gmail.com"><i class="fas fa-envelope" aria-hidden="true"></i> josemiguelsantost@gmail.com</a>
</p>
</div>

## Highlights

- 🏆 **1st place, RoboRacer category – International Robot Olympiad (IRO) Open Ecuador 2025**, autonomous racing on the F1TENTH platform with ROS 2 ([details](/portfolio/2025-f1tenth-championship)).
- 🤖 **QUPA** – designed and built a modular ESP32-based robotic platform for multi-robot research, validated in ARGoS/Gazebo and in physical multi-robot experiments ([details](/portfolio/qupa)).
- 🔬 Research internship at the **RISE Lab, Sungkyunkwan University** (Feb–May 2024). Worked on mobile robot navigation with ROS and Gazebo, including SLAM (ROS1) and the implementation of MPPI and MPC controllers (ROS2) for a Hyundai Robotics project. Tested on TurtleBot3 ([details](/portfolio/2024-skku-internship)).

## Featured Projects

{% assign featured = site.portfolio | sort: 'order' %}
<div class="project-grid">
{% for post in featured limit:3 %}{% include project-card.html %}{% endfor %}
</div>

[See all projects →](/portfolio/)

## Technical Skills

<p class="skills-group">Robotics</p>
<ul class="chips"><li>ROS / ROS 2</li><li>Gazebo</li><li>ARGoS</li><li>RViz</li><li>SLAM</li><li>Nav2</li><li>MoveIt</li><li>TurtleBot3</li><li>F1TENTH</li></ul>

<p class="skills-group">Control</p>
<ul class="chips"><li>MPC</li><li>MPPI</li><li>PID</li><li>Social Force Models</li><li>Gap Follower</li></ul>

<p class="skills-group">Programming</p>
<ul class="chips"><li>Python</li><li>C++</li><li>MATLAB</li><li>Lua</li><li>JavaScript</li><li>G-Code</li></ul>

<p class="skills-group">Embedded / Hardware</p>
<ul class="chips"><li>ESP32</li><li>LiDAR</li><li>Camera perception</li><li>Sensor integration</li><li>Actuator control</li></ul>

## About Me

I am José Miguel Santos Terán, a Mechatronics Engineer from Escuela Superior Politécnica del Litoral (ESPOL). My work focuses on autonomous robotics, distributed systems, and swarm robotics. I am interested in how groups of small robots can sense their environment, make local decisions, and coordinate to perform tasks in complex environments.

My research combines mechanical design, embedded systems, perception, and multi-robot simulation. I work with platforms such as ARGoS, Gazebo, and ROS to study collective robotic behavior and evaluate distributed control strategies in both simulated and real robotic systems.

## Research Interests

My main research interests include:

- Swarm robotics and multi-robot systems  
- Distributed and decentralized control  
- Simulation of collective robotic behaviors  
- Autonomous robotic platforms with onboard sensing and computation  
- Experimental validation of robotic algorithms  

I am particularly interested in robotic collectives capable of performing inspection, monitoring, and cooperative manipulation tasks in real environments.

## QUPA Robotic Platform

During my undergraduate thesis I developed QUPA, a modular robotic platform designed for experimentation in distributed robotic systems.

<div style="text-align:center; margin-bottom:30px;">
<iframe width="800" height="450" 
src="https://www.youtube.com/embed/ogbKXia1wyc" 
title="QUPA Swarm Simulation" 
frameborder="0" 
allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
allowfullscreen>
</iframe>
</div>

The project included the design and integration of:

- A compact robotic platform with an embedded controller based on ESP32  
- A manipulation module for object interaction  
- Onboard perception using camera-based color detection  
- Energy and actuator analysis for a resource-constrained robotic system  
- Simulation environments in ARGoS and Gazebo to evaluate multi-robot behavior  

The platform was tested both in simulation and in physical experiments. Through experiments with multiple robots, I evaluated how increasing the number of robots affects task completion time and efficiency. These experiments allowed me to explore how simple local rules can produce cooperative behavior in groups of robots.

More technical details about the platform, including simulation environments and system architecture, can be found in the portfolio section.

<div style="text-align:center; margin-top:40px;">
<img src="/images/qupa_Real.jpeg" width="500" alt="QUPA modular mobile robot prototype">
</div>

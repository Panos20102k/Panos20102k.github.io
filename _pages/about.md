---
layout: single
title: ""
permalink: /
author_profile: true
---

# About Me

I am a PhD student in Systems Engineering at Cornell University, advised by Prof. [Andreas Malikopoulos](https://ids-lab.net/). 
I work on learning-based control methods for multi-robot systems. I operate the [LIMO ROS2 robots](https://global.agilex.ai/products/limo-ros2).

Previously, I was a graduate researcher at the [Institute of Automotive Technology](https://www.mos.ed.tum.de/ftm/startseite/) at the Technical University of Munich (TUM), advised by Dr. [Simon Sagmeister](https://www.mos.ed.tum.de/ftm/personen/mitarbeiter/simon-sagmeister-m-sc/), team lead of [TUM Autonomous Motorsport](https://www.mos.ed.tum.de/en/ftm/main-research/intelligent-vehicle-systems/tum-autonomous-motorsport/).

I received my Diploma (integrated Bachelor & Master) in Mechanical Engineering from the National Technical University of Athens (NTUA) with a GPA of 8.82/10.00, which ranked in the top 3.57%.

---

<!-- --- -->

<!-- # News

1. **Feb 2026** – Paper accepted at IEEE CDC 2026.
2. **Jan 2026** – Released new GitHub repository on Hamiltonian residual learning.
3. **Dec 2025** – Presented work at [Conference Name].
4. **Aug 2025** – Started PhD at Cornell University.

--- -->
# Projects
## Real-Time Optimal Multi-Robot Navigation

In this project, we developed a machine learning-based algorithm for real-time multi-robot navigation with joint optimiziation of the robots' trajectories. To achieve this we leverage graph neural networks to accelerate the solution of the multi-robot mixed-integer quadratic program (MIQP). The navigation stack that we developed in this work is validated on the LIMO ROS2 robots, showcasing solution of the multi-robot MIQP in less than every 200 ms, with vehicle speeds up to 0.5 m/sec.

- 📄 [Paper](https://ieeexplore.ieee.org/abstract/document/11312656)
<!-- - 💻 [GitHub Repository](https://github.com/Panos20102k/Multi-Limo-Control) -->
- 🎥 Project Video:

<iframe width="560" height="315" 
src="https://www.youtube.com/embed/3Of0j3a5fGw" 
frameborder="0" 
allowfullscreen>
</iframe>

---

## Optimal Control for Unknown Dynamics

I analyzed and implemented a novel framework for safety-constrained continuous optimal control problems with unknown system dynamics. I derived its theoretical results based on convex analysis and Pontryagin's Minimum Principle and validated the framework on a cruise control application to real wheeled robots.

- 📄 [Paper](https://arxiv.org/abs/2603.27677)
- 💻 [GitHub Repository](https://github.com/Panos20102k/Multi-Limo-Control) 
- 🎥 [Project Video](https://www.youtube.com/watch?v=pMSZKlU5O44)

<!-- <iframe width="560" height="315" 
src="https://www.youtube.com/watch?v=pMSZKlU5O44" 
frameborder="0" 
allowfullscreen>
</iframe> -->

I analyzed and implemented a new algorithm for optimal control problems with unknown system dynamics based on dynamic programming and stochastic gradient descent. I also implemented benchmark reinforcement learning algorithms: Policy Gradient, Random Search and Q-learning, and compared them with our own developed framework in the linear quadratic regulator problem.

- 📄 [Paper](https://arxiv.org/abs/2510.00308)
- 💻 [GitHub Repository](https://github.com/Panos20102k/Learning-LQR)

I implemented a gradient-free stochastic optimization algorithm on linear systems and validated its theoretical robustness properties

- 📄 [Paper](https://arxiv.org/abs/2506.12596)

---

## Vehicle Dynamics Modeling for Autonomous Racing

In this project, I developed a vehicle model to enable a thorough evaluation of vehicle motion controllers in
simulation: Diploma Thesis. 

- 📄 [Paper](https://dspace.lib.ntua.gr/xmlui/handle/123456789/58426)

I then contributed to an extension of this model, which now runs on the
software stack of the TUM Autonomous Motorsport team and is used to evaluate vehicle motion
controllers in simulation. The model is validated against data recorded from the fastest lap of TUM Autonomous Motorsport in Monza 2023, with vehicle speeds up to 267 km/h.

- 📄 [Paper](https://ieeexplore.ieee.org/abstract/document/10588858)
- 💻 [GitHub Repository](https://github.com/TUMFTM/Open-Car-Dynamics)
- 🎥 [Project Video](https://www.youtube.com/watch?v=2uVidmMZ9ns)

<!-- <iframe width="560" height="315" 
src="https://www.youtube.com/watch?v=2uVidmMZ9ns" 
frameborder="0" 
allowfullscreen>
</iframe> -->

---

# Fellowships & Awards

- Cornell Systems Engineering Fellowship (2024-2025)
- IEEE CDC 2025 Student Travel Award
- ACC 2026 Student Travel Award

---

# Teaching

- Lead Teaching Assistant – CEE 3040 Uncertainty Analysis in Engineering (Cornell, Fall 2025)
- Teaching Assistant – CEE 6080 Optimal Control & Decision Theory (Cornell, Spring 2026)

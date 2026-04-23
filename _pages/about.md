---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p class="profile-intro">PhD researcher at <a href="https://robots.ihmc.us/">IHMC</a> in Pensacola, FL, working at the intersection of classical control theory and deep reinforcement learning for humanoid robot locomotion and recovery. My broader interests span mathematical optimization, physics-informed learning, and the principled design of autonomous systems.</p>

## Education

| | Institution | |
|--|-------------|--|
| **Ph.D., Robotics** | IHMC / University of West Florida · Pensacola, FL | in progress |
| **M.Sc., Applied Mathematics** | Northeastern University · Boston, MA | 2020 |
| **B.Tech., Mechanical Engineering** | NMIMS · Mumbai, India | 2018 |

## Research

I am a PhD researcher at the [Institute for Human and Machine Cognition (IHMC)](https://robots.ihmc.us/) in Pensacola, FL — one of the world's leading humanoid robotics laboratories.

My doctoral work focuses on **physics-embedded reinforcement learning for humanoid balance and recovery**. Decades of classical control research produced compact, interpretable representations of balance — capture point, centroidal momentum, wrench-feasibility regions — that modern RL has largely discarded. I embed these physical invariants directly into the training process as privileged critic inputs and reward structure, enabling humanoid robots to discover emergent multi-contact recovery behaviors without any prescribed contact schedule.

The target is a single policy governing the complete loco-manipulation recovery loop: stable walking → external disturbance → fall → multi-contact stand-up → task resumption.

<div class="research-metrics">
  <div class="metric">
    <div class="metric-value">93.4%</div>
    <div class="metric-label">fall recovery rate across all test configurations</div>
  </div>
  <div class="metric">
    <div class="metric-value">emergent</div>
    <div class="metric-label">multi-contact strategies — elbows, knees, forearms</div>
  </div>
  <div class="metric">
    <div class="metric-value">one</div>
    <div class="metric-label">unified policy for the full recovery loop</div>
  </div>
</div>

## Experience

**PhD Researcher — IHMC / University of West Florida** · Pensacola, FL
- Physics-embedded RL for humanoid robot balance and recovery
- Asymmetric actor-critic architecture with privileged balance signals: capture point, CoM, centroidal momentum
- 93.4% fall recovery rate; emergent multi-contact strategies across elbows, knees, and forearms
- [Lab website](https://robots.ihmc.us/)

**Research Engineer — DEKA Research & Development Corp.** · Manchester, NH
- Autonomous Delivery Robot: deep learning sensor fusion for global occupancy grids (lidar, radar, cameras)
- Insulin Pump Enhancement: reinforcement learning and transformer methods for adaptive insulin delivery
- Infusion Pump Analysis: vision-based liquid flow rate estimation

**ML Research Assistant — Nano-medicine Center, Northeastern University** · Boston, MA
- Automated MRI classification for Alzheimer's disease (83% accuracy)
- Segmentation models for gray matter characterization from structural MR images

## Technical Skills

**Programming** &nbsp;·&nbsp; Python &nbsp;·&nbsp; C++ &nbsp;·&nbsp; Java &nbsp;·&nbsp; MATLAB

**Simulation & Robotics** &nbsp;·&nbsp; Isaac Sim &nbsp;·&nbsp; IsaacLab &nbsp;·&nbsp; MuJoCo &nbsp;·&nbsp; ROS &nbsp;·&nbsp; sim-to-real transfer

**Control Theory** &nbsp;·&nbsp; classical controls &nbsp;·&nbsp; capture-point dynamics &nbsp;·&nbsp; centroidal momentum &nbsp;·&nbsp; wrench-feasibility analysis

**Machine Learning** &nbsp;·&nbsp; PyTorch &nbsp;·&nbsp; CUDA &nbsp;·&nbsp; reinforcement learning &nbsp;·&nbsp; transformer architectures &nbsp;·&nbsp; Scikit-Learn

**Tools** &nbsp;·&nbsp; NumPy &nbsp;·&nbsp; Pandas &nbsp;·&nbsp; OpenCV &nbsp;·&nbsp; Linux

## Selected Projects

[**RUL-Aircraft**](https://github.com/NeharPoddar/RUL-aircraft) — Predicting remaining useful life of aircraft engines with deep learning on the NASA C-MAPSS dataset.

[**Patterns in Capset**](https://github.com/NeharPoddar/patterns-in-capset) — Combinatorics research exploring attribute distributions in the cap set problem.

---

<div class="profile-links">
  <a href="/publications/">Publications</a>
  <a href="https://neharpoddar.github.io/files/NeharPoddarCurriculumVitae .pdf">CV</a>
  <a href="/hobbies/">Hobbies</a>
  <a href="mailto:poddar.nehar@gmail.com">Contact</a>
</div>

---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* BTech in Mechanical Engineering, NMIMS, Mumbai, India
* MSc in Applied Mathematics, Northeastern University, Boston, USA
* Ph.D. in Robotics, [IHMC](https://robots.ihmc.us/) / University of West Florida (in progress)
  * Dissertation: Physics-Embedded Reinforcement Learning for Multi-Contact Balance in Humanoid Robots

Work Experience
======
* **PhD Researcher — IHMC / University of West Florida** (Pensacola, FL)
  * Physics-embedded reinforcement learning for humanoid robot balance and recovery
  * Asymmetric actor-critic with privileged balance signals (capture point, CoM, centroidal momentum)
  * 93.4% fall recovery rate across all configurations; emergent multi-contact strategies

* **Machine Learning Engineer — DEKA Research and Development Corp.** (Manchester, NH)
  * Autonomous Delivery Robot: deep learning sensor fusion for global occupancy grids (lidar, radar, cameras)
  * Insulin Pump Enhancement: Reinforcement Learning and Transformer methods for adaptive insulin delivery
  * Infusion Pump Analysis: vision-based liquid flow rate estimation

* **Machine Learning and Statistics Research Assistant — Nano-medicine Center, Northeastern University**
  * Automated MRI classification for Alzheimer's disease (83% accuracy)
  * Segmentation models for extracting gray matter characteristics from MR images

* **Teaching Assistant and Grader — Northeastern University**
  * Mathematical methods, mathematical modeling, and calculus

Skills
======
* **Programming:** Python, C++, MATLAB
* **ML/DL:** PyTorch, CUDA, Scikit-Learn
* **Robotics:** ROS, MuJoCo, reinforcement learning, sim-to-real transfer
* **Tools:** Pandas, NumPy, OpenCV, Linux

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

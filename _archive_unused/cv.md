---
permalink: /cv/
title: "CV"
redirect_from:
  - /resume
---

<a class="cv-download" href="/files/NeharPoddar_CV.pdf">Download PDF ↓</a>

## Education

<div class="entry">
  <div class="entry-body">
    <div class="entry-title">PhD in Robotics</div>
    <div class="entry-meta">IHMC &amp; University of West Florida <span class="mono">· 2024–present</span></div>
    <ul>
      <li>Advisor: Prof. Robert Griffin</li>
      <li>Research: humanoid fall recovery, embedding classical balance metrics (capture point, centroidal momentum) into reinforcement learning as reward and critic structure, extended to perception-guided, environment-assisted recovery.</li>
    </ul>
  </div>
</div>
<div class="entry"><div class="entry-body"><div class="entry-title">MSc, Applied Mathematics</div><div class="entry-meta">Northeastern University <span class="mono">· 2019–2021</span></div></div></div>
<div class="entry"><div class="entry-body"><div class="entry-title">BSc, Mechanical Engineering</div><div class="entry-meta">NMIMS, Mumbai <span class="mono">· 2015–2019</span></div></div></div>

## Research Experience

<div class="entry">
  <div class="entry-body">
    <div class="entry-title">PhD Researcher — IHMC / University of West Florida</div>
    <div class="entry-meta"><span class="mono">Jan 2024 – present</span></div>
    <ul>
      <li>Led <em>Bounce Back</em>, a perception-guided framework that composes walking, recovery, and environment-assisted interaction, enabling a humanoid to detect and transiently exploit nearby walls and tables as physical supports.</li>
      <li>Built a perception-conditioned mixture-of-experts policy: warm-started trainable experts from the independently trained walking, get-up, and bracing specialists, then combined them into a unified actor via a learned softmax gate conditioned on a robot-centric 3D occupancy representation and proprioception.</li>
      <li>Trained the unified policy end-to-end using PPO, advantage-weighted imitation, and entropy-regularized gating, with the frozen specialists supplying imitation targets and privileged-critic inputs, and a learned residual correction enabling adaptation beyond the experts' initial action space.</li>
      <li>Designed a physics-informed asymmetric actor–critic incorporating center-of-mass dynamics, capture point, and centroidal momentum as privileged training signals while retaining deployable observations for the actor.</li>
      <li>Created a success-gated curriculum spanning standing, falling, ankle and hip recovery, stepping, and multi-contact stand-up, enabling a single reference-free policy to adapt across substantially different body configurations and disturbance magnitudes.</li>
      <li>Achieved 93.4% recovery success across 10,000 trials on the Unitree H1-2 in simulation; evaluated via MuJoCo sim-to-sim testing across five initial configurations and 0–500&nbsp;N perturbations.</li>
      <li>Demonstrated zero-shot deployment on H1-2 hardware at 50&nbsp;Hz, recovering from supine, seated, kneeling, and crouched configurations using proprioceptive sensing.</li>
      <li>Performed controlled ablations isolating the contributions of privileged learning, physics-informed reward structure, and curriculum design to recovery performance.</li>
    </ul>
  </div>
</div>

<div class="entry">
  <div class="entry-body">
    <div class="entry-title">ML &amp; Statistics Research Assistant — Nano-Medicine Center, Northeastern University</div>
    <div class="entry-meta"><span class="mono">Jan 2020 – May 2020</span></div>
    <ul>
      <li>Built an SVM-based classification pipeline on whole-brain MRI data for Alzheimer's diagnosis (83% cross-validated accuracy).</li>
      <li>Trained a 3D UNet segmentation model to extract gray matter regions for downstream classification.</li>
    </ul>
  </div>
</div>

## Industry Experience

<div class="entry">
  <div class="entry-body">
    <div class="entry-title">Research Engineer — DEKA Research and Development Corp.</div>
    <div class="entry-meta"><span class="mono">Jan 2021 – Jan 2024</span> · Autonomous Delivery Robot, FedEx ROXO</div>
    <ul>
      <li>Developed multi-modal perception for an autonomous delivery robot, fusing lidar, radar, monocular, and stereo cameras into unified 3D occupancy and drivability representations.</li>
      <li>Built RGB-D semantic segmentation, stereo depth completion, surface-normal estimation, and 3D reconstruction pipelines for environment and terrain understanding.</li>
      <li>Engineered active-learning and uncertainty-estimation pipelines spanning data collection, model training, evaluation, and deployment on autonomous robotic systems.</li>
      <li>Deployed semantic segmentation for surface classification (84% accuracy) and self-attention-based scene-text recognition (94% accuracy) on a production robotic platform.</li>
      <li>Implemented RANSAC, PnP, ICP, and sensor-calibration pipelines in ROS/C++, reducing calibration time from 60 to 3 minutes.</li>
    </ul>
    <p class="muted" style="margin:10px 0 0;"><strong>Medical Devices</strong></p>
    <ul>
      <li>Modeled insulin dynamics using coupled differential equations and explored reinforcement learning for adaptive control under partial observability.</li>
      <li>Developed vision-based flow estimation and temporal signal processing for medical infusion monitoring.</li>
    </ul>
  </div>
</div>

## Publications

See the [Publications page](/publications/) for the full list with abstracts, links, and video. In brief:

<ul>
  <li><strong>Bounce Back: Perception-Guided, Environment-Assisted Humanoid Skill Resumption</strong> — submitted to IEEE Robotics and Automation Letters (RA-L), 2027 <span class="tag">Work in progress</span></li>
  <li><strong>Embedding Classical Balance Control Principles in Reinforcement Learning for Humanoid Recovery</strong> — submitted to IEEE-RAS Humanoids, 2026 · <a href="https://arxiv.org/abs/2603.08619">arXiv</a></li>
  <li><strong>Accelerating Classical Path Planning via Learned Search Space Reduction</strong> — AIAA SciTech Forum, 2026 (Nominated for Best Student Paper)</li>
  <li><strong>Anticipatory and Adaptive Footstep Streaming for Teleoperated Bipedal Robots</strong> — IEEE-RAS Humanoids, 2025</li>
</ul>

## Skills

<div class="skills-row"><span class="label">Learning &amp; Control</span><span>Reinforcement Learning, PPO, Actor–Critic Methods, Model-Based Control, Optimal Control, Curriculum Learning, Sim-to-Real Learning</span></div>
<div class="skills-row"><span class="label">Humanoid Robotics</span><span>Whole-Body Control, Balance, Multi-Contact Interaction, Centroidal Dynamics, Capture Point, Contact Modeling, Stability and Recovery</span></div>
<div class="skills-row"><span class="label">Perception</span><span>3D Occupancy Maps, Depth Estimation, Surface Normals, Semantic Segmentation, Sensor Fusion, LiDAR, Radar, Stereo Vision, RGB-D</span></div>
<div class="skills-row"><span class="label">Robotics Systems</span><span>Isaac Lab, Isaac Sim, MuJoCo, PyTorch, CUDA, ROS/ROS2, Linux</span></div>
<div class="skills-row"><span class="label">Programming</span><span>Python, C++, MATLAB, NumPy, OpenCV, Scikit-Learn</span></div>

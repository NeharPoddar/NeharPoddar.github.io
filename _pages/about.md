---
permalink: /
title: ""
redirect_from:
  - /about/
  - /about.html
  - /publications/
  - /cv/
---

<div class="intro">
  <img class="headshot" src="/images/headshot.jpg" alt="Nehar Poddar">
  <div class="name-block">
    <h1>Nehar Poddar</h1>
    <p class="tagline">PhD researcher, humanoid robotics &amp; reinforcement learning</p>
  </div>
</div>

<p class="contact-line">
  <a href="mailto:poddar.nehar@gmail.com">Email</a><span class="sep">·</span><a href="https://linkedin.com/in/neharpoddar">LinkedIn</a><span class="sep">·</span><a href="https://scholar.google.com/citations?user=sEJbLWwAAAAJ&hl=en">Google Scholar</a><span class="sep">·</span><a href="https://github.com/NeharPoddar">GitHub</a><span class="sep">·</span><a href="https://robots.ihmc.us/">Lab</a><span class="sep">·</span><a href="/files/NeharPoddar_CV.pdf">CV (PDF)</a>
</p>

I'm a PhD researcher at [IHMC](https://robots.ihmc.us/) and the University of West Florida, working at the intersection of reinforcement learning, classical control, and perception. My research is about enabling humanoid robots to maintain balance, adapt to their environment, and compose learned behaviors — embedding classical balance metrics (capture point, centroidal momentum) directly into RL as reward and critic structure, most recently extended to perception-guided, environment-assisted recovery.

Before my PhD I was a research engineer at [DEKA](https://www.dekaresearch.com/), building perception and calibration systems for FedEx's autonomous delivery robot, and a research assistant applying ML to MRI-based Alzheimer's classification at Northeastern.

## Publications

<div class="pub">
  <img class="pub-thumb" src="/images/alex-crossing-arms.jpg" alt="Alex humanoid robot">
  <div class="pub-body">
    <div class="pub-title">Bounce Back: Perception-Guided, Environment-Assisted Humanoid Skill Resumption</div>
    <div class="pub-venue"><span class="tag">Work in progress</span>submitted to IEEE Robotics and Automation Letters (RA-L), 2027</div>
    <p class="pub-desc">N. Poddar et al. — A perception-guided mixture-of-experts framework: walking, unassisted get-up, and environment-assisted bracing specialists, warm-started into trainable experts and recombined by a learned softmax gate conditioned on a robot-centric 3D occupancy map, so the robot can detect and transiently brace against nearby walls or tables during recovery.</p>
  </div>
</div>

<div class="pub">
  <img class="pub-thumb" src="/images/h1-2-clean.png" alt="Unitree H1-2 humanoid robot">
  <div class="pub-body">
    <div class="pub-title">Embedding Classical Balance Control Principles in Reinforcement Learning for Humanoid Recovery</div>
    <div class="pub-venue"><span class="tag">Submitted</span>IEEE-RAS International Conference on Humanoid Robots (Humanoids), 2026 · <a href="https://arxiv.org/abs/2603.08619">arXiv</a></div>
    <p class="pub-desc">N. Poddar et al. — A single RL policy embeds capture point, CoM state, and centroidal momentum as privileged critic inputs and physics-guided rewards, spanning ankle/hip/stepping disturbance rejection through multi-contact stand-up. 93.4% in-distribution recovery across 10,000 trials on the Unitree H1-2, validated via MuJoCo sim-to-sim testing and zero-shot hardware deployment.</p>
    <video controls preload="none" poster="/images/h1-2-full.webp">
      <source src="/files/iros2026-video.mp4" type="video/mp4">
    </video>
  </div>
</div>

<div class="pub">
  <div class="pub-body">
    <div class="pub-title">Accelerating Classical Path Planning via Learned Search Space Reduction</div>
    <div class="pub-venue">AIAA SciTech Forum, 2026 · <strong>Nominated for Best Student Paper</strong> · <a href="https://arc.aiaa.org/doi/abs/10.2514/6.2026-1997">AIAA Arc</a></div>
    <p class="pub-desc">N. Poddar, B. Mishra, G. Clark, H. E. Sevil, R. Griffin — A learned model prunes the search space for classical planners (A*, RRT) by predicting which regions are unlikely to contain optimal paths, focusing computation where it matters with minimal solution-quality loss.</p>
  </div>
</div>

<div class="pub">
  <div class="pub-body">
    <div class="pub-title">Anticipatory and Adaptive Footstep Streaming for Teleoperated Bipedal Robots</div>
    <div class="pub-venue">IEEE-RAS Humanoids, 2025 · <a href="https://arxiv.org/abs/2508.11802">arXiv</a> · <a href="https://ieeexplore.ieee.org/abstract/document/11203044/">IEEE Xplore</a> · <a href="https://youtu.be/E_X6ol7BoyQ">Video</a></div>
    <p class="pub-desc">L. Penco, B. Park, S. Fasano, N. Poddar, S. McCrory, N. Kitchel, T. Bialek, D. Anderson, D. Calvert, R. Griffin — Retargets and anticipates operator footsteps for teleoperated bipedal locomotion on uneven terrain, validated on the humanoid robot Nadia.</p>
  </div>
</div>

<p class="small"><a href="https://scholar.google.com/citations?user=sEJbLWwAAAAJ&hl=en">Full list on Google Scholar →</a></p>

## Experience

<div class="entry">
  <img class="entry-thumb" src="/images/h1-2-clean.png" alt="Unitree H1-2">
  <div class="entry-body">
    <div class="entry-title">PhD Researcher — IHMC / University of West Florida</div>
    <div class="entry-meta"><span class="mono">Jan 2024 – present</span> · Advisor: Prof. Robert Griffin</div>
    <ul>
      <li>Leading <em>Bounce Back</em>, a perception-guided mixture-of-experts policy that composes walking, get-up, and environment-assisted bracing into one unified controller.</li>
      <li>Built a physics-informed asymmetric actor–critic embedding capture point, CoM, and centroidal momentum as privileged signals — 93.4% recovery success across 10,000 trials on the Unitree H1-2, validated in MuJoCo sim-to-sim and zero-shot on hardware.</li>
    </ul>
  </div>
</div>

<div class="entry">
  <img class="entry-thumb" src="/images/roxo.jpeg" alt="FedEx ROXO delivery robot">
  <div class="entry-body">
    <div class="entry-title">Research Engineer — DEKA Research and Development Corp.</div>
    <div class="entry-meta"><span class="mono">Jan 2021 – Jan 2024</span></div>
    <ul>
      <li>Built multi-modal perception (lidar, radar, stereo/mono cameras) for FedEx's autonomous delivery robot, ROXO.</li>
      <li>RGB-D segmentation, depth completion, and active-learning pipelines; RANSAC/PnP/ICP calibration cutting setup time from 60 to 3 minutes.</li>
      <li>Also worked on insulin pump control (RL for adaptive delivery), infusion-pump flow estimation, and vision-based organ-transport monitoring.</li>
    </ul>
  </div>
</div>

<div class="entry">
  <div class="entry-body">
    <div class="entry-title">ML Research Assistant — Nano-Medicine Center, Northeastern University</div>
    <div class="entry-meta"><span class="mono">Jan 2020 – May 2020</span></div>
    <ul>
      <li>SVM classification on whole-brain MRI for Alzheimer's diagnosis (83% cross-validated accuracy); 3D U-Net segmentation for gray-matter regions.</li>
    </ul>
  </div>
</div>

## Education

<div class="entry"><div class="entry-body"><div class="entry-title">PhD in Robotics</div><div class="entry-meta">IHMC &amp; University of West Florida <span class="mono">· 2024–present</span></div></div></div>
<div class="entry"><div class="entry-body"><div class="entry-title">MSc, Applied Mathematics</div><div class="entry-meta">Northeastern University <span class="mono">· 2019–2021</span></div></div></div>
<div class="entry"><div class="entry-body"><div class="entry-title">BSc, Mechanical Engineering</div><div class="entry-meta">NMIMS, Mumbai <span class="mono">· 2015–2019</span></div></div></div>

## Skills

<div class="skills-row"><span class="label">Learning &amp; Control</span><span>Reinforcement learning (PPO, actor–critic), model-based control, curriculum learning, sim-to-real</span></div>
<div class="skills-row"><span class="label">Robotics</span><span>Whole-body control, balance, multi-contact interaction, capture point, centroidal dynamics</span></div>
<div class="skills-row"><span class="label">Perception</span><span>3D occupancy mapping, semantic segmentation, sensor fusion, LiDAR / radar / stereo</span></div>
<div class="skills-row"><span class="label">Systems</span><span>Isaac Lab, Isaac Sim, MuJoCo, PyTorch, CUDA, ROS/ROS2, Linux</span></div>
<div class="skills-row"><span class="label">Languages</span><span>Python, C++, MATLAB, Java</span></div>

## Robots I've worked with

<div class="gallery">
  <figure>
    <img src="/images/alex-crane-kick.jpg" alt="Alex, IHMC humanoid, dynamic pose">
    <figcaption>Alex — IHMC</figcaption>
  </figure>
  <figure>
    <img src="/images/alex-crossing-arms.jpg" alt="Alex, IHMC humanoid">
    <figcaption>Alex — IHMC</figcaption>
  </figure>
  <figure>
    <img src="/images/h1-2-full.webp" alt="Unitree H1-2">
    <figcaption>Unitree H1-2</figcaption>
  </figure>
  <figure>
    <img src="/images/go2-profile.jpeg" alt="Unitree Go2">
    <figcaption>Unitree Go2</figcaption>
  </figure>
  <figure>
    <img src="/images/roxo.jpeg" alt="FedEx ROXO">
    <figcaption>FedEx ROXO — DEKA</figcaption>
  </figure>
</div>

<img src="/images/alex-poses.gif" alt="Alex recovery poses" style="max-width:260px;border-radius:8px;border:1px solid var(--line);margin-top:14px;">

## Outside the lab

I play alto saxophone with [PBC Band](https://www.pbcband.org/), a community band in Pensacola. Also into chess, running, hiking, photography, and board games.

<hr>

<p class="small"><a href="mailto:poddar.nehar@gmail.com">Get in touch</a></p>

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
    <p class="tagline">I teach robots to hold their balance, move with purpose, and actually be useful 🤖</p>
  </div>
</div>

<p class="contact-line">
  <a href="mailto:poddar.nehar@gmail.com">Email</a><span class="sep">·</span><a href="https://linkedin.com/in/neharpoddar">LinkedIn</a><span class="sep">·</span><a href="https://scholar.google.com/citations?user=sEJbLWwAAAAJ&hl=en">Google Scholar</a><span class="sep">·</span><a href="https://github.com/NeharPoddar">GitHub</a><span class="sep">·</span><a href="https://robots.ihmc.us/">Lab</a><span class="sep">·</span><a href="/files/NeharPoddar_CV.pdf">CV (PDF)</a>
</p>

I am a PhD researcher at the <strong><a href="https://robots.ihmc.us/">Institute for Human &amp; Machine Cognition (IHMC)</a></strong> and the <strong>University of West Florida</strong>, working at the intersection of <strong>reinforcement learning, classical control, and perception</strong>.

My research explores how humanoid robots can <strong>maintain balance, recover from failure, exploit useful contacts in their environment, and return to purposeful behavior</strong>.

I combine physically meaningful representations of balance and contact with reinforcement learning and perception, with the goal of building robots that can <strong>reason about their own bodies and interact intelligently with the physical world</strong>.

Before my PhD, I was a Research Engineer at <strong><a href="https://www.dekaresearch.com/">DEKA Research &amp; Development</a></strong>, where I developed perception and calibration systems for FedEx's autonomous delivery robot, ROXO.

## Research

<p class="lead">Building humanoids that can recover and adapt</p>

Humanoid robots operate in physical environments where unexpected events are unavoidable: a disturbance can push the robot outside its support region, a fall can change its configuration, and nearby objects may become useful sources of support.

My research asks:

<blockquote>How can a humanoid use learning, physical reasoning, and its environment to remain capable when things go wrong?</blockquote>

I approach this through three connected areas.

### Physics-embedded reinforcement learning

I incorporate physically meaningful representations, including center of mass, capture point, centroidal momentum, and contact stability, into reinforcement learning through reward design and privileged critic information.

Rather than learning balance entirely from raw observations, the policy is trained with structure that reflects the underlying physics of humanoid motion.

### Environment-assisted recovery

I develop perception-guided policies that let humanoids recognize and exploit nearby walls, tables, and other surfaces when recovering from a loss of balance.

The robot learns when and how to establish temporary contacts, coordinate its whole body around those contacts, and transition back to stable, free-standing locomotion.

### Composable whole-body behavior

I combine specialized learned behaviors into systems that operate continuously rather than relying on hand-designed mode switches.

The broader goal is a humanoid that can walk, lose balance, recover, interact with its surroundings, and resume its task as one coherent system.

## Selected Publications

<div class="pub-list">

<div class="pub">
  <img class="pub-thumb" src="/images/alex-crossing-arms.jpg" alt="Alex humanoid robot" style="object-position: 50% 18%;">
  <div class="pub-body">
    <div class="pub-title">Bounce Back: Perception-Guided, Environment-Assisted Humanoid Skill Resumption</div>
    <div class="pub-venue"><span class="tag">Work in progress</span>submitted to IEEE Robotics and Automation Letters (RA-L), 2027</div>
    <div class="pub-authors">N. Poddar et al.</div>
    <p class="pub-desc">A perception-guided framework for humanoid recovery that combines walking, get-up, and environment-assisted bracing. Specialized behaviors are warm-started into trainable experts and recombined through a learned policy conditioned on a robot-centric 3D occupancy representation, allowing the robot to detect and transiently brace against nearby surfaces during recovery.</p>
  </div>
</div>

<div class="pub">
  <img class="pub-thumb" src="/images/unitree-g1.jpg" alt="Unitree G1 humanoid robot" style="object-position: 50% 20%;">
  <div class="pub-body">
    <div class="pub-title">HANDOFF: Humanoid Agentic Task-Space Whole-Body Control via Distilled Complementary Teachers</div>
    <div class="pub-venue"><span class="tag">Under review</span>CoRL 2026 submission</div>
    <div class="pub-authors">L. Yang, J. Li, N. Poddar, Y. Hou, G. Huh, R. Griffin, G. Gkioxari, A. D. Ames</div>
    <p class="pub-desc">Distills complementary teacher policies into a single agentic whole-body controller for task-space humanoid manipulation.</p>
  </div>
</div>

<div class="pub">
  <img class="pub-thumb" src="/images/h1-2-full.webp" alt="Unitree H1-2 humanoid robot" style="object-position: 50% 10%;">
  <div class="pub-body">
    <div class="pub-title">Embedding Classical Balance Control Principles in Reinforcement Learning for Humanoid Recovery</div>
    <div class="pub-venue"><span class="tag">Submitted</span>IEEE-RAS International Conference on Humanoid Robots (Humanoids), 2026 · <a href="https://arxiv.org/abs/2603.08619">arXiv</a></div>
    <div class="pub-authors">N. Poddar et al.</div>
    <p class="pub-desc">A reinforcement-learning framework that embeds capture point, center-of-mass state, and centroidal momentum into privileged critic inputs and physics-guided rewards. The learned policy spans disturbance rejection through multi-contact stand-up recovery on the Unitree H1-2. The policy achieved <strong>93.4%</strong> recovery success across <strong>10,000 trials</strong>, with validation through MuJoCo sim-to-sim testing and zero-shot hardware deployment.</p>
    <video controls preload="none">
      <source src="/files/iros2026-video.mp4" type="video/mp4">
    </video>
  </div>
</div>

<div class="pub">
  <div class="pub-thumb-spacer"></div>
  <div class="pub-body">
    <div class="pub-title">Accelerating Classical Path Planning via Learned Search Space Reduction</div>
    <div class="pub-venue">AIAA SciTech Forum, 2026 · <strong>Nominated for Best Student Paper</strong> · <a href="https://arc.aiaa.org/doi/abs/10.2514/6.2026-1997">AIAA Arc</a></div>
    <div class="pub-authors">N. Poddar, B. Mishra, G. Clark, H. E. Sevil, R. Griffin</div>
    <p class="pub-desc">A learned model reduces the search space explored by classical planners such as A* and RRT, focusing computation on regions more likely to contain high-quality solutions while maintaining solution quality.</p>
  </div>
</div>

<div class="pub">
  <div class="pub-thumb-spacer"></div>
  <div class="pub-body">
    <div class="pub-title">Anticipatory and Adaptive Footstep Streaming for Teleoperated Bipedal Robots</div>
    <div class="pub-venue">IEEE-RAS Humanoids, 2025 · <a href="https://arxiv.org/abs/2508.11802">arXiv</a> · <a href="https://ieeexplore.ieee.org/abstract/document/11203044/">IEEE Xplore</a> · <a href="https://youtu.be/E_X6ol7BoyQ">Video</a></div>
    <div class="pub-authors">L. Penco, B. Park, S. Fasano, N. Poddar, S. McCrory, N. Kitchel, T. Bialek, D. Anderson, D. Calvert, R. Griffin</div>
    <p class="pub-desc">A footstep-streaming system that anticipates operator motion and adapts footsteps for teleoperated bipedal locomotion over uneven terrain, validated on the Nadia humanoid robot.</p>
  </div>
</div>

</div>

<p class="small"><a href="https://scholar.google.com/citations?user=sEJbLWwAAAAJ&hl=en">Full list on Google Scholar →</a></p>

## Experience

<div class="entry">
  <img class="entry-thumb" src="/images/alex-crane-kick.jpg" alt="Alex, IHMC humanoid robot" style="object-position: 50% 8%;">
  <div class="entry-body">
    <div class="entry-title">PhD Researcher</div>
    <div class="entry-org">IHMC / University of West Florida</div>
    <div class="entry-meta"><span class="mono">Jan 2024 – present</span> · Advisor: Prof. Robert Griffin</div>
    <ul>
      <li>Developing learning-based methods for humanoid balance, recovery, locomotion, and environmental interaction.</li>
      <li>Built a physics-informed asymmetric actor–critic framework incorporating capture point, center-of-mass dynamics, and centroidal momentum as privileged training signals.</li>
      <li>Developed perception-guided recovery using walking, get-up, and environment-assisted bracing behaviors conditioned on 3D environmental representations.</li>
      <li>Achieved <strong>93.4%</strong> recovery success across <strong>10,000 H1-2 trials</strong>, followed by MuJoCo sim-to-sim validation and zero-shot hardware deployment at 50&nbsp;Hz.</li>
      <li>Designed controlled ablations to evaluate the contribution of privileged physical information, physics-informed rewards, and curriculum learning.</li>
      <li>Working across reinforcement learning, classical control, whole-body control, perception, contact dynamics, and robot simulation.</li>
    </ul>
  </div>
</div>

<div class="entry">
  <img class="entry-thumb" src="/images/roxo.jpeg" alt="FedEx ROXO delivery robot">
  <div class="entry-body">
    <div class="entry-title">Research Engineer</div>
    <div class="entry-org">DEKA Research and Development Corp.</div>
    <div class="entry-meta"><span class="mono">Jan 2021 – Jan 2024</span></div>
    <ul>
      <li>Built multimodal perception systems combining LiDAR, radar, stereo cameras, and monocular cameras into unified 3D occupancy and drivability representations for FedEx's autonomous delivery robot, ROXO.</li>
      <li>Developed and deployed RGB-D semantic segmentation achieving <strong>84% accuracy</strong> on the production platform.</li>
      <li>Developed self-attention-based scene-text recognition achieving <strong>94% accuracy</strong>.</li>
      <li>Implemented RANSAC, PnP, and ICP-based sensor calibration in ROS/C++, reducing setup time from approximately <strong>60 minutes to 3 minutes</strong>.</li>
      <li>Also contributed to learning-based medical-device systems, including RL for adaptive insulin delivery under partial observability, infusion-pump flow estimation, and vision-based organ-transport monitoring.</li>
    </ul>
  </div>
</div>

<div class="entry">
  <img class="entry-thumb" src="/images/brain-mri.jpg" alt="Sagittal brain MRI" title="MRI: Oliver Stollmann, CC BY, via Wikimedia Commons">
  <div class="entry-body">
    <div class="entry-title">ML Research Assistant</div>
    <div class="entry-org">Nano-Medicine Center, Northeastern University</div>
    <div class="entry-meta"><span class="mono">Jan 2020 – May 2020</span></div>
    <ul>
      <li>Developed machine-learning methods for whole-brain MRI classification and segmentation.</li>
      <li>Achieved <strong>83% cross-validated accuracy</strong> for Alzheimer's disease classification using SVMs.</li>
      <li>Developed a 3D U-Net for brain-region segmentation.</li>
    </ul>
  </div>
</div>

## Education

<div class="edu-row">
  <div><span class="edu-degree">PhD in Robotics</span><span class="edu-school">IHMC &amp; University of West Florida</span></div>
  <div class="edu-date mono">2024 – present</div>
</div>
<div class="edu-row">
  <div><span class="edu-degree">MSc, Applied Mathematics</span><span class="edu-school">Northeastern University</span></div>
  <div class="edu-date mono">2019 – 2021</div>
</div>
<div class="edu-row">
  <div><span class="edu-degree">BSc, Mechanical Engineering</span><span class="edu-school">NMIMS, Mumbai</span></div>
  <div class="edu-date mono">2015 – 2019</div>
</div>

## Technical Skills

<div class="skills-row"><span class="label">Robotics &amp; Control</span><span>Humanoid locomotion, whole-body control, balance control, multi-contact interaction, contact dynamics, capture-point dynamics, centroidal dynamics, model-based control, sim-to-real</span></div>
<div class="skills-row"><span class="label">Machine Learning</span><span>Reinforcement learning, PPO, actor–critic methods, physics-informed learning, curriculum learning, deep learning, PyTorch</span></div>
<div class="skills-row"><span class="label">Perception</span><span>3D occupancy mapping, sensor fusion, semantic segmentation, LiDAR, radar, stereo vision, RGB-D perception</span></div>
<div class="skills-row"><span class="label">Simulation &amp; Systems</span><span>Isaac Lab, Isaac Sim, MuJoCo, ROS/ROS2, CUDA, Linux</span></div>
<div class="skills-row"><span class="label">Programming</span><span>Python, C++, MATLAB, Java</span></div>

## Robotic Platforms

<div class="gallery">
  <figure>
    <img src="/images/alex-crossing-arms.jpg" alt="Alex, IHMC humanoid, dynamic pose" style="object-position: 50% 12%;">
    <figcaption>Alex, IHMC</figcaption>
    <p class="gallery-desc">Humanoid locomotion, balance, whole-body control, and recovery.</p>
  </figure>
  <figure>
    <img src="/images/h1-2-full.webp" alt="Unitree H1-2">
    <figcaption>Unitree H1-2</figcaption>
    <p class="gallery-desc">RL-based balance and recovery, multi-contact stand-up, sim-to-sim transfer, and hardware deployment.</p>
  </figure>
  <figure>
    <img src="/images/go2-profile.jpeg" alt="Unitree Go2">
    <figcaption>Unitree Go2</figcaption>
    <p class="gallery-desc">Learning-based locomotion and robot simulation.</p>
  </figure>
  <figure>
    <img src="/images/roxo.jpeg" alt="FedEx ROXO">
    <figcaption>FedEx ROXO, DEKA</figcaption>
    <p class="gallery-desc">Multimodal perception, occupancy mapping, calibration, and autonomous navigation.</p>
  </figure>
</div>

## Outside the Lab

I play alto saxophone with <a href="https://www.pbcband.org/">PBC Band</a>, a community band in Pensacola. Outside robotics, I enjoy chess, running, hiking, photography, board games, and trying new food.

## Get in Touch

<p class="lead" style="text-align:center;">Interested in humanoid robots, embodied intelligence, or physically grounded learning?</p>

<p style="text-align:center;"><a class="cv-download" href="mailto:poddar.nehar@gmail.com">poddar.nehar@gmail.com</a></p>

<p class="contact-line" style="text-align:center;">
  <a href="https://linkedin.com/in/neharpoddar">LinkedIn</a><span class="sep">·</span><a href="https://scholar.google.com/citations?user=sEJbLWwAAAAJ&hl=en">Google Scholar</a><span class="sep">·</span><a href="https://github.com/NeharPoddar">GitHub</a>
</p>

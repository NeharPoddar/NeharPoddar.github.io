---
title: "**PhD Researcher** <br/> **Humanoid Robotics & Reinforcement Learning** <br/> Institute for Human and Machine Cognition (IHMC)"
excerpt: "**Duration**: 2025 - Present"
collection: portfolio
---

I am a PhD researcher at [IHMC](https://robots.ihmc.us/), one of the world's leading humanoid robotics laboratories, affiliated with the University of West Florida.

## Research Focus: Physics-Embedded RL for Humanoid Recovery

My doctoral research addresses a core open problem in humanoid robotics: robust fall recovery and multi-contact balance. Classical controllers require pre-specified contact sequences; vanilla RL policies lack the balance structure to discover multi-contact strategies. My approach embeds classical balance invariants — capture point, center-of-mass dynamics, centroidal momentum — directly into the reinforcement learning training process.

**Key contributions:**
- Asymmetric actor-critic architecture: critic receives privileged balance signals during training; actor deploys on proprioception only
- 93.4% fall recovery rate across the full configuration space (supine, seated, kneeling, crouching)
- Emergent multi-contact recovery strategies (elbows, forearms, knees) with no prescribed contact schedules
- Zero-shot sim-to-real transfer via asymmetric training

## Projects

- **Armatrix–IsaacLab** ([GitHub](https://github.com/NeharPoddar/Armatrix--IsaacLab)): GPU-accelerated robot learning framework built on NVIDIA Isaac Sim — the primary research codebase for RL training and evaluation
- **Accelerating Classical Path Planning via Learned Search Space Reduction** — AIAA SCITECH 2026

[IHMC Robotics Lab](https://robots.ihmc.us/)

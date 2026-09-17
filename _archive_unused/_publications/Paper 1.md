---
title: "Embedding Classical Balance Control Principles in Reinforcement Learning for Humanoid Recovery"
collection: publications
excerpt: "We show that injecting classical balance metrics — capture point, center-of-mass state, and centroidal momentum — as privileged critic inputs and physics-grounded reward terms enables a single RL policy to recover from any initial pose (supine, seated, kneeling, crouching) with 93.4% success, using emergent multi-contact strategies (elbows, knees, forearms) without prescribed contact schedules."
date: 2026-03-01
venue: "IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS 2026)"
paperurl: "https://arxiv.org/abs/2603.08619"
citation: "Poddar, N. (2026). Embedding Classical Balance Control Principles in Reinforcement Learning for Humanoid Recovery. <i>IROS 2026</i>."
---

**TL;DR:** Physics-grounded RL for humanoid fall recovery. Classical balance metrics (capture point, CoM, centroidal momentum) as privileged critic inputs → 93.4% recovery from any pose, emergent multi-contact behavior, zero-shot sim-to-real via asymmetric actor-critic.

## Abstract

Humanoid fall recovery remains an open problem: classical controllers require pre-specified contact sequences, while vanilla RL policies lack the balance structure to discover multi-contact strategies. We propose an asymmetric actor-critic architecture in which the critic receives privileged balance signals — capture point error, CoM height and velocity, centroidal momentum — during training, while the actor relies solely on proprioception at deployment. This separation grounds the reward in interpretable physics, making it resistant to exploitation, and preserves sim-to-real transfer for signals that are difficult to estimate reliably on hardware during uncontrolled falls.

A single policy trained without reference trajectories or scripted contact schedules achieves **93.4% recovery** across the full configuration space: supine, seated, kneeling, and crouching. The policy spontaneously discovers contact strategies using elbows, forearms, and knees — behaviors that were not prescribed by the reward structure. Ablation without the physics-embedded components causes stand-up learning to fail entirely (stuck-low termination rate rises from 0.067 to 1.0).

## Key Results

| Metric | Value |
|---|---|
| Recovery rate (full config. space) | **93.4%** |
| Stuck-low rate (ours) | 0.067 |
| Stuck-low rate (no physics embedding) | 1.0 (never stands up) |
| Contact strategies discovered | Elbows, forearms, knees (emergent) |
| Reference trajectories required | None |
| Prescribed contact schedules | None |

## Method

- **Asymmetric actor-critic**: critic trained with privileged balance info, actor deploys on proprioception only
- **Physics-grounded reward**: capture point error drives actor toward recoverable states without reward hacking
- **Curriculum**: graduated recovery configurations from simple to full configuration space
- **Architecture**: fully proprioceptive actor → zero-shot hardware transfer

[arXiv:2603.08619](https://arxiv.org/abs/2603.08619)

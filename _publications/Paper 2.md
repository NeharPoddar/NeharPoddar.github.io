---
title: "Balance as Infrastructure: Environmental Contact Awareness for Loco-Manipulation Recovery in Humanoid Robots"
collection: publications
excerpt: "Extending physics-embedded RL from recovery-as-goal to balance-as-infrastructure: a single policy that walks, handles perturbations, exploits environmental contacts (walls, tables) to extend stability regions, and carries objects through recovery — without dropping them."
date: 2027-01-01
venue: "In preparation"
paperurl:
citation:
---

**Status:** In preparation (thesis chapter 2, IHMC / University of West Florida)

## Motivation

Paper 1 treats recovery as the terminal goal: Fall → Stand up → Done. Paper 2 reframes balance as persistent infrastructure: Walk → Pushed → Recover → Keep walking. The key shift is that balance is always on, not activated only during emergencies.

## Core Technical Contribution

Nobody has closed the loop from surface detection → stability region extension → recovery contact selection in a single learned policy. This work proposes to do exactly that by extending the asymmetric actor-critic from Paper 1 with an **environmental contact opportunity map** in the critic:

- **Nearby surface positions and normals** (walls, tables, pillars)
- **Reachability flags** for each candidate contact surface
- **Wrench-feasibility rewards** that generalize beyond flat-ground capture point (handles slopes, vertical contacts)

At deployment, the privileged contact map is replaced with lightweight depth sensing or height maps — same actor architecture, real sensors.

## The Selling Experiment

Robot falls toward a wall → extends arm to brace against it → recovers, because the critic learned that the wall extends the horizontal capture point margin. A baseline policy without the contact map ignores the wall and fails to recover.

## Loco-Manipulation

The most practically important capability: balance-aware recovery while carrying an object. A grasp-maintenance reward causes the policy to stiffen its grip as balance is challenged, maintaining payload through perturbation and recovery. No mode switching, no object-drop.

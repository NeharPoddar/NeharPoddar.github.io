---
title: "Accelerating Classical Path Planning via Learned Search Space Reduction"
collection: publications
excerpt: "A learned model prunes the search space for classical path planners (A*, RRT), predicting which regions are unlikely to contain optimal paths and focusing computation where it matters — yielding significant speedups with minimal solution quality degradation."
date: 2026-01-06
venue: "AIAA SCITECH 2026 Forum"
paperurl: "https://arc.aiaa.org/doi/abs/10.2514/6.2026-1997"
citation: "Poddar, N., Mishra, B., Clark, G., Sevil, H. E., & Griffin, R. (2026). Accelerating Classical Path Planning via Learned Search Space Reduction. <i>AIAA SCITECH 2026 Forum</i>. https://doi.org/10.2514/6.2026-1997"
---

**TL;DR:** Neural search space reduction for classical planners. A learned model identifies low-value regions before planning begins, letting A*/RRT spend computation only where optimal paths are likely to exist.

## Abstract

Classical path planning algorithms such as A* and RRT are computationally expensive in high-dimensional or cluttered environments because they explore large portions of the search space before finding a solution. We propose a learned search space reduction approach that uses a neural model to predict which regions of the configuration space are unlikely to contain optimal paths, pruning them before planning begins. This focuses planner effort on promising regions, yielding significant speedups with minimal solution quality degradation. Presented at the AIAA SCITECH 2026 Forum.

## Links

- [AIAA Arc](https://arc.aiaa.org/doi/abs/10.2514/6.2026-1997)
- DOI: 10.2514/6.2026-1997

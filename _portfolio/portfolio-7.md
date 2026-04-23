---
title: "**Remaining Useful Life Prediction** <br/> **Aircraft Engine Health Monitoring** <br/> Machine Learning Research Project"
excerpt: "AI techniques to predict failure trends and remaining useful life in aircraft engines"
collection: portfolio
---

Accurate prediction of Remaining Useful Life (RUL) in aircraft engines is critical for aviation maintenance — enabling early detection of potential failures, timely component replacement, and improved operational safety.

## Overview

This project focuses on preprocessing sensor data from the **C-MAPSS (Commercial Modular Aero-Propulsion System Simulation)** dataset and building machine learning models to predict RUL. The goal: uncover underlying degradation patterns from raw sensor streams and build reliable predictive models for a mission-critical aviation challenge.

## Technical Approach

- **Data preprocessing:** RUL calculation, normalization, feature engineering from multi-sensor time series
- **Models explored:** LSTM-based sequence models, gradient-boosted trees, and classical regression baselines
- **Evaluation:** Root mean square error (RMSE) on held-out engine run-to-failure trajectories

## Key Results

- Achieved competitive RMSE on C-MAPSS benchmarks
- Identified dominant sensor channels contributing to degradation signal
- Demonstrated data-driven approach is viable for fleet-scale predictive maintenance

[GitHub Repository](https://github.com/NeharPoddar/RUL-aircraft)

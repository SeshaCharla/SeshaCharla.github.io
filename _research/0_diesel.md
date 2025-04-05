---
layout: page
title: "Diesel Engine After-treatment System Diagnostics"
summary: "Developed a discrete switched nonlinear model that captures the measured dynamics of the system for aging diagnostics. The aging effects are captured in the directional variation in the model parameters."
image: "/assets/cummins/sys.png"
permalink: /research/cummins_project/
---

<img src="/assets/cummins/sys.png" width="700">

### Problem
- Determine the catalyst aging in-situ from the truck data.

### Objective
- A reduced order model with detectable unknowns that reflect aging with bounded uncertainty.

### Requirements:
- Identifiability
- Robustness of aging signatures and detection mechanisms

<img src="/assets/cummins/SCR-ASC_ModelReduction_horizontal.png" width="700">

## Key Results

### Dynamic Modelling: Discrete Switched Nonlinear Model
- Two-fold prediction improvement compared to CSTR model
- Interplay between residence time and sampling
- Catalyst Saturation and Desaturation

<img src="/assets/cummins/automata.png" width="500">

### Parameter and State Estimation:
- Nonlinear Model that is Linear in Parameters
- Observer for catalyst storage
- Saturated system identification using linear programming.

<img src="/assets/cummins/aging.png" width="400">

### Aging Signatures:
- Saturated Catalyst System Parameters
- Test statistic that has statistically different mean.


## Key Learnings

### Statistical Signal Processing: Estimation and Detection
- Sum of Squares filtering
- Kalman Filter
- Statistical Detection Theory
- Set Membership Filtering and Estimation

### System Identification:
- Recursive Least-squares
- Persistence of Excitation (PE) and Parsimony
- Closed-Loop System Identification

### Dynamic Modelling:
- Discrete Systems
- Small Perturbation and Averaging in Nonlinear Systems
- First Principles modelling
- Uncertainty Modelling

### Control Theory and Nonlinear Analysis:
- Stability of switched systems
- Handling parameter uncertainties


### Programming Languages:
- Python (Analysis, signal processing, optimization, plotting)
- Matlab (System ID tool-box)
- C++ (eigen, CMake, )

### Convex Optimization

## Industry Collaboration
- Worked with the Aftertreatment systems Team at Cummins on this project with bi-weekly presentations and discussions.
- Developed and submitted research proposals for the years 2024 and 2025 (≈120k total grant yearly)

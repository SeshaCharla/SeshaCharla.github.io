---
layout: page
title: "Trajectory Generation of Hybrid Linear-affine Systems under Polytopic Uncertainities and Constraints"
summary: "Developed a simplex-chain generation algorithm which can be used for motion planning of hybrid linear-affine systems under polytopic uncertianities and constraints. The simplices form the sequence control-barrier functions satisfying the desired constraints."
image: "/assets/RCP/main_fig.png"
permalink: /research/rcp/
---

<img src="/assets/RCP/1D.gif" width="300">

## Objective
- Design a series of simplices that correspond to affine feedback controllers that guarantee safety using restricted facets under polytopic uncertainties and constraints.

## Theory and Demonstration
<iframe src="/assets/RCP/theory.pdf" width="700px" height="450px"></iframe>

## Key Learning and Tools
- Convex optimization (Disciplined convex programming (CVX library)) and Linear Matrix Inequalities (LMIs).
- Computational Geometry for defining constraints for convex optimization problem (CDD library in Python)
- Switching systems and stability, common Lyapunov functions
- Python

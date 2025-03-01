---
layout: page
title: "Research Engineer - Estimation and Control Systems - SC Solutions (Internship)"
summary: "Developed an estimation framework for lean-to-fat ratio in meat using computer vision and nonlinear filtering techniques."
image: "/assets/SC/fat_est.png"  # Ensure this image exists or remove this line
permalink: /projects/sc-solutions-fat-estimation/
start_date: 2023-05-15
end_date: 2023-08-11
---

# Fat Estimation from Vision Data
**Project Duration:** {{ page.start_date | date: "%B %Y" }} – {{ page.end_date | date: "%B %Y" }}

<img src="/assets/SC/fat_est.png" width="800">

## Overview
During my time as a **Research Engineer Intern** at **SC Solutions**, I worked on a **USDA-funded project** focused on **automating fat estimation in meat processing**. The goal was to replace manual classification methods with a **computer vision-based approach** for determining the lean-to-fat (LTF) ratio in meat cuts.

## Key Contributions
- Developed an estimation framework to classify meat based on LTF ratios using image processing and statistical modeling.
- Implemented computer vision techniques for fat and lean segmentation using RGB and LAB color spaces.
- Built a C++ image processing pipeline for real-time estimation.
- Optimized estimation accuracy by correlating surface-level fat patterns with full-volume fat distribution.

## Key Results
- Achieved a **feasible estimation model** for LTF classification.
- Developed a **scalable C++ framework** for processing **large video datasets** efficiently.
- Enabled **automated fat estimation**, for improving consistency.

## Demonstration
<video width="560" height="315" controls>
  <source src="/assets/videos/speed_run.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>



## Technologies Used
- Computer Vision (OpenCV, Image Processing)
- Machine Learning (CNNs using PyTorch)
- C++ (CMake, OpenCV, Pybind11)

---

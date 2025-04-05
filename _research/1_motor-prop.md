---
layout: page
title: "Multirotor Actuators: Identification, Adaptive Robust Control and Fault Diagnosis"
summary: "Developed an estimation and adaptive-robust control framework for uncertainity rejection and fault diagnosis using rotor angular velocity feedback from back-emf signals"
image: "/assets/motor-prop/motor-prop.png"
permalink: /research/motor-prop/
---

<img src="/assets/motor-prop/motor-prop.png" width="500">

## Objective
- Improve the dynamic response of the actuator using angular velocity feedback.
- Use the real-time parameter estimates to detect and diagnose actuator faults.


## Key Results
- Identified and corrected for the input uncertainty due to unknown nonlinear filter in the ESC.
- The real-time parameter estimates converge to the actual values under PE.
- Proposed a fault detection and isolation framework based on the change in parameter estimates

<img src="/assets/motor-prop/param_est.png" width="700">

## Implementation in NI-MyRIO
- LabView is used for basic IO operations and signal processing, PWM generation and the Real-Time loop.
- Cross compiled C++ (.so files) shared libraries are used for the main computations at every sampling time.
- Interrupt based RPM Sensing Algorithm
- RPM sensing algorithm in FPGA to reduce interrupt load on CPU.

<img src="/assets/motor-prop/implementation.png" width="300">

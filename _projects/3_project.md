---
layout: page
title: Bipedal Training of Spot using IsaacLab & PPO
description: Training Boston Dynamics' Spot to balance on two legs using reinforcement learning.
img: assets/img/spot_balancing.jpg
importance: 3
category: work
---

## Overview
This project focuses on training **Boston Dynamics' Spot** to balance and move on two legs using **IsaacLab** and **Proximal Policy Optimization (PPO)**. By leveraging **reinforcement learning (RL)** in simulation, the goal is to improve Spot's **stability, balance, and adaptability** in real-world environments.

## **Key Features & Technologies**
- **IsaacLab Simulation**:
  - Utilized **NVIDIA Isaac Gym** to simulate Spot’s physics-based interactions.
  - Enabled real-time reinforcement learning for **bipedal stability**.
- **Reinforcement Learning with PPO**:
  - Trained Spot to stand, balance, and walk on two legs.
  - Reward functions designed to improve stability and minimize oscillations.
- **Training Metrics**:
  - **Reward Optimization**: Maximized balance duration.
  - **Adaptive Learning**: Improved Spot’s response to disturbances.

## Project Showcase

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <video controls class="img-fluid rounded z-depth-1">
            <source src="/assets/video/rl_training_2.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <p class="caption">Reinforcement learning progress over iterations.</p>
    </div>
</div>

## Future Work
- Improve **real-world transfer learning** for deployment on actual Spot hardware.
- Enhance **locomotion efficiency** by refining reward structures.
- Extend training for **obstacle avoidance and dynamic terrain adaptation**.

## Explore More
- [Project Repository](https://github.com/abhismirai10/IsaacLab_Abhi)

This project showcases advancements in **robotic locomotion and AI-driven control strategies**, paving the way for more adaptive robotic quadrupeds.
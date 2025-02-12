---
layout: page
permalink: /research/
title: Research
description: Exploring advanced robotics through classical and End-to-End Learning methods
nav: true
nav_order: 2
---

<!-- _pages/research.md -->

## Overview
My research focuses on advancing robotics by transitioning from **classical control methods** to **reinforcement and imitation learning-based approaches** for robotic manipulation. The goal is to develop **adaptive**, **cost-effective**, and **scalable** systems that can operate efficiently in dynamic real-world environments.

> **Key Areas of Focus**:  
> - Classical robotics techniques for task precision and stability.  
> - AI-driven learning methods like **Action Chunking with Transformers (ACT) and Proximal Policy Optimization (PPO)** for adaptability.  
> - Scalable hardware setups for real-world integration.

---

## Classical Robotics: Pick-and-Place Pipeline
- **Framework**: Built using the **Drake robotics framework** with a robotic manipulator.
- **Key Features**:
  - Spatial transformations and precise trajectory execution.
  - **Pseudoinverse-based inverse kinematics** for accurate positioning.
- **Limitations**:
  - Sensitive to object variations and lacks real-time adaptability.
  - Struggles with **kinematic singularities**.

> **Demo Video**: [Pick-and-Place Pipeline](https://youtu.be/gP7TM4Jf5zs)

---

## Learning-Based Approaches: ACT, Diffusion Policies, and PPO

### 1. Action Chunking with Transformers (ACT)
- **Focus**: Predicting coherent action sequences to minimize errors.
- **Techniques**:
  - **Action Chunking**: Groups actions for smooth execution.
  - **Temporal Ensembling**: Reduces abrupt transitions.
- **Applications**:
  - Pick-and-place tasks, object sliding.
- **Advantage**: Ensures superior motion fluidity.

> **Demo Video**: [ACT in Action](https://youtu.be/bIt4VxzjvIM)

---

### 2. Diffusion Policies
- **Focus**: High-precision trajectory refinement through iterative denoising.
- **Techniques**:
  - Models trajectory distributions in action space.
  - Iteratively adjusts actions for real-time variations.
- **Applications**:
  - Object stacking, complex orientations.
- **Advantage**: Handles **dynamic environmental changes** effectively.

> **Demo Video**: [Diffusion Policies in Action](https://youtu.be/O8il1sL_Z9A)

---

### 3. Proximal Policy Optimization (PPO)
- **Focus**: Learning optimal robotic control policies via reinforcement learning.
- **Techniques**:
  - Trains policies through trial-and-error interaction with the environment.
  - Balances exploration and exploitation for stability.
- **Applications**:
  - Autonomous robotic grasping and adaptive manipulation.
- **Advantage**: Achieves **higher success rates in uncertain environments**.

> **Demo Video**: [PPO in Action](https://youtu.be/mHlaLGXJQWI)

---

## Experimental Results

The research evaluated different learning methods across various robotic tasks. Proximal Policy Optimization (PPO) consistently outperformed Action Chunking with Transformers (ACT) and Diffusion Policies, demonstrating higher adaptability and efficiency in dynamic environments. PPO achieved an 88% success rate in pick-and-place tasks, while Diffusion Policies led object orientation tasks with an 83% success rate. ACT performed best for smooth task execution, especially in motion-sensitive tasks like object sliding and stacking.

> **Insights**:
> - **ACT**: Best for smooth and consistent execution.
> - **Diffusion Policies**: Excels in high-precision tasks.
> - **PPO**: Achieves the highest adaptability in **uncertain environments**.

---

## Hardware Setup

### Leader-Follower Robotic Arm System
- **Leader Arm**: Controlled by a human operator for task demonstration.
- **Follower Arm**: Mimics the leader’s movements to collect high-quality training data.
- **Features**:
  - **6-DoF robotic manipulators** with Dynamixel servos.
  - **Dual RGB cameras** for workspace coverage and real-time processing.

> **Image**:  
![Hardware Setup](/assets/img/research_setup.jpg)

---

## References
For additional technical details and algorithms, refer to my **[Master’s Thesis](/assets/pdf/Chothani-Thesis-2024.pdf)** or
[More Results Demos](https://drive.google.com/drive/u/0/folders/1LftoRg34HieBMN42KgWSghgstuSexj5M)
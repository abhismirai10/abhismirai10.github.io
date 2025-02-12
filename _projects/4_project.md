---
layout: page
title: Mirai3_0 Pose-Based Drone Control
description: A gesture-controlled drone navigation system leveraging pose estimation for a seamless user experience.
img: assets/img/mirai3_0.jpg
importance: 4
category: work
---

## Overview
**Mirai3_0** is a **pose-based drone control system** designed to interpret **human gestures as flight commands**, making drone navigation more **intuitive, accessible, and fun**. This system enhances real-time interaction by enabling drones to respond dynamically to human movement.

### **Key Features & Technologies**
- **Pose Estimation**: Utilizes **MediaPipe** to detect and classify **33 body keypoints**.
- **Dataset**:
  - **1,600 images** with **8 different poses**:
    - Takeoff, Land, Up, Forward, Backward, Right, Left, Do Nothing.
- **Model Development**:
  - Converts pose data into flight commands using a classification model.
- **Drone Control System**:
  - **PX4 Autopilot** integrated via **MAVSDK-Python**.
  - Relays commands from human gestures to drone flight maneuvers.
  - Real-time sensor feedback ensures stability and precision.

## Project Showcase

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pose_drone_1.jpg" title="Pose-based drone control in action" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pose_drone_2.jpg" title="Different pose commands for navigation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The Mirai3_0 system enables intuitive drone control through predefined human poses.
</div>

## Future Work
- Expand pose recognition to **include more commands**.
- Implement **object detection and tracking** for more precise interaction.
- Integrate **self-supervised learning** to enhance autonomous capabilities.

## Explore More
- [Project Repository](https://github.com/abhismirai10/Gesture_Control_Drone)

Mirai3_0 is a step towards a more **intuitive, AI-driven approach to drone navigation**, breaking barriers in human-robot interaction.
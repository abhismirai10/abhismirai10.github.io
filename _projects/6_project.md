---
layout: page
title: Pan and Tilt Object Tracking System
description: A robotic pan-and-tilt mechanism for real-time object tracking using YOLO and Dynamixel servos.
img: assets/img/pan_tilt_tracking.jpg
importance: 6
category: work
related_publications: false
---

## Overview
This project involves designing and implementing a **pan-and-tilt mechanism** for **real-time object tracking**, leveraging **Dynamixel servos** for smooth motion control and **YOLO-based object detection** to identify and track targets dynamically.

## **Key Features & Technologies**
- **Mechanical Design**:
  - Fully designed and simulated in **Fusion 360**.
  - **Lightweight and modular** design for adaptability.
- **Servo Control**:
  - Utilized **Dynamixel servos** for precise pan-and-tilt motion.
  - Implemented **PID control** for smooth tracking movements.
- **Object Detection & Tracking**:
  - Integrated **YOLOv10** for **real-time object detection**.
  - Optimized **bounding box tracking** with Kalman Filters for stability.
  - Implemented **multi-object tracking** for dynamic environments.

## Project Showcase

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <video controls class="img-fluid rounded z-depth-1">
            <source src="/assets/video/pan_tilt.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <p class="caption">Reinforcement learning progress over iterations.</p>
    </div>
</div>

## Future Work
- Improve **object tracking speed** with model optimizations.
- Implement **gesture-based tracking control**.
- Integrate **edge AI** for onboard processing without external computing.

## Explore More
- [Project Repository](https://github.com/abhismirai10/Pan-and-Tilt-Mechanism)

This project demonstrates advanced **robotic vision and motion control**, making it applicable to **surveillance, automation, and human-robot interaction**.

---
layout: page
title: "Robot Manipulation"
description: "Hexapod Manipulation for Industrial Deployment"
img: assets/img/psa.jpg
importance: 2
category: work
related_publications: false
---


## Overview

**Industrial Collaboration with the Port of Singapore Authority (PSA)**

This is focused on the development and deployment of a legged manipulation framework on a hexapod robot for efficient twist-lock operations in container handling. Twist-locks are omnipresent in container management, wwhether on ports or ships. The project aims to reduce the human effort and risk involved in this highly abundant yet perilious job. The project explores real-world applications of legged robotics in industrial automation. I am working as the part of the horizontal placement team, on hexapod locomotion and manipulkation. 

<div class="text-center">
    <div class="col-sm-6 mx-auto mt-3 mt-md-0">
        {% include video.liquid path="assets/video/psa.mp4" loop=true muted=true autoplay=true width="100%" %}
        <div class="caption text-center">Manipulation of twist-lock for pick-up and carrying on the base of the robot.</div>
    </div>
</div>


## **Technical Implementation**
### **Legged Locomotion & Manipulation Control**
- Developed a **hybrid locomotion-manipulation framework**, where the **front legs of the hexapod** transition into **manipulators** with gripper attached. While the remaining legs enable finer adjustment for twist-lock deployment and pickup.
- Implemented **gait adaptation**, allowing the hexapod to **stabilize** while executing precise **twist-lock engagement and disengagement**.

### **Hardware & Simulation**
- **PyBullet simulation**: Modeled the **hexapod**, its manipulators, and the twist-lock system for **offline trajectory testing** designed for safe yet precise manipulation.
- **HEBI API Control**: Used for actuators on motors for real world deployment.
- **Gait transition testing**: Simulated **walking to manipulation shifts** under different load conditions.






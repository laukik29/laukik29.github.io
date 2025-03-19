---
layout: page
title: "SpiderBot"
description: "A custom-designed symmetrical hexapod robot with 3DoF per leg."
img: assets/img/spiderbot.jpg
importance: 1
category: work
related_publications: false
---


## Overview

<div class="row">
    <div class="col-sm mt-3 mt-md-0" style="max-width: 50%; margin: auto;">
        {% include figure.liquid loading="eager" path="assets/img/spiderbot.jpg" title="example image" class="img-fluid rounded z-depth-1" style="width: 100%; max-width: 400px;" %}
    </div>
</div>


**SpiderBot** is a **custom-designed symmetrical hexapod robot** developed as part of the **Electronics and Robotics Club, BITS Goa**. Each of its six legs has **3 degrees of freedom (3DoF)**, allowing for precise and adaptive locomotion. The robot is designed to navigate various terrains using **bio-inspired control mechanisms**. We deployed a **central pattern generator (CPG) controller to achieve gaits for locomotion**.



## **Key Features**
- **Custom-designed & manufactured** from ground up symmetrical hexapod with **3DoF per leg**.
- Developed and tested multiple **gait patterns**, including:
  - **3-3 tripod gait** (faster, stable)
  - **4-2 gait** (adaptive to rough terrains)
- Implemented a **bio-inspired Central Pattern Generator (CPG) controller** for **smooth and adaptive locomotion**.
- Conducted extensive testing on **trotting, on-spot twisting, and terrain adaptation** in real-world environments.
- **Secured 2nd position** at the **Open Design Contest**, conducted by the Department of Electrical and Electronics Engineering. <a href="assets/pdf/Design_Contest.pdf" target="_blank">Certificate</a>


- **Achieved external control capability**, enabling remote navigation & motion demonstrations.
<div class="row">
    <div class="col-sm mt-3 mt-md-0" style="max-width: 30%; margin: auto;">
        {% include figure.liquid loading="eager" path="assets/img/spiderbot3.JPG" title="example image" class="img-fluid rounded z-depth-1" style="width: 100%; max-width: 400px;" %}
    </div>
</div>
---

## Walking Demonstrations

<div class="container">
    <div class="row justify-content-center"> 

<!-- Video 1 -->
<div class="col-md-4 col-sm-12">
            {% include video.liquid path="assets/video/spider_walk.mp4" loop=true muted=true autoplay=true width="100%" %}
            <div class="caption text-center">Initial testing</div>
        </div>

<!-- Video 2 -->
<div class="col-md-4 col-sm-12">
            {% include video.liquid path="assets/video/spider_walk2.mp4" loop=true muted=true autoplay=true width="100%" %}
            <div class="caption text-center">Multiple gaits</div>
        </div>

<!-- Video 3 -->
<div class="col-md-4 col-sm-12">
            {% include video.liquid path="assets/video/spider_rot.mp4" loop=true muted=true autoplay=true width="100%" %}
            <div class="caption text-center">On-spot twisting</div>
        </div>

</div>
</div>



---

## SpiderBot Prototype
<div class="row">
    <div class="col-sm mt-3 mt-md-0" style="max-width: 40%; margin: auto;">
        {% include figure.liquid loading="eager" path="assets/img/spiderbot2.JPG" title="example image" class="img-fluid rounded z-depth-1" style="width: 100%; max-width: 400px;" %}
    </div>
</div>
<div class="caption">
    SpiderBot the headliner of QUARK 2022, technical fest project display.
</div>

---

## Development & Team Leadership
- **Led a team of 25 students** over two years to design, build, and test SpiderBot.
- Managed **electronics, mechanical, and software development** teams.
- Designed **custom made pcb** for power distribution and **raspi-arduino interface** via rosserial.
- Achieved the **first successful hardware implementation** of the hexapod.
- Developed a **CPG-based controller**, enabling smooth gait transitions.


---
## Project Repository
[**SpiderBot GitHub Repository**](https://github.com/ERC-BPGC/SpiderBot/)

## Additional Notes
[Slides](assets/pdf/spiderbot.pdf)







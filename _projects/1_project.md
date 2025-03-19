---
layout: page
title: End-to-End RL policy for Stair Locomotion
description: PPO-based DRL control for hexapods and quadrupeds
img: assets/img/yuna.jpg
importance: 1
category: work
related_publications: false
---

This project explores **end-to-end reinforcement learning** for **stair locomotion** using **hexapod (Yuna) and quadruped robots**. We train a parallel **Proximal Policy Optimization (PPO) based DRL control policy** to achieve robust stair climbing capabilities.
I used isaac_gym implementation based on isaacsim for parallel simulation. 


<!-- To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    --- -->

<div class="row">
    <!-- Left Image -->
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/yuna2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>

<!-- Middle Video -->
<div class="col-sm mt-3 mt-md-0">
    <video autoplay loop muted playsinline class="img-fluid rounded z-depth-1" style="width: 100%; max-height: 100%;">
        <source src="{{ 'assets/video/yuna_flat.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support the video tag.
    </video>
</div>


<!-- Right Image -->
<div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/yuna_sim.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    On the left, yuna - a hexapod from HEBI robotics. Middle, Locomotion policy trained on flat ground. Right, Locomotion policy being trained on stairs.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <video autoplay loop muted playsinline class="img-fluid rounded z-depth-1" style="width: 100%;">
            <source src="{{ 'assets/video/yuna_stair2.mp4' | relative_url }}" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>
<div class="caption">
    Trained RL hexapod policy
</div>

Key Observation : Hexapods (Yuna) being inherently stable, need more penalties than positive rewards for tasks such as climbing stairs as opposed to in quadrupeds.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <video autoplay loop muted playsinline class="img-fluid rounded z-depth-1" style="width: 100%;">
            <source src="{{ 'assets/video/yuna_stair.mp4' | relative_url }}" type="video/mp4">
            Your browser does not support the video tag.
        </video>
    </div>
</div>
<div class="caption">
    Training policy walking on rough terrain, sloped terrain, stairs up/down, and discrete obstacles
</div>

<!-- </div>
<!-- <div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<!-- ``` --> 

<!-- {% endraw %} -->

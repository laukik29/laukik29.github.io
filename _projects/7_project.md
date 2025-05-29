---
layout: page
title: "APEX: Action Priors Enable Efficient Exploration for Skill Imitation on Articulated Robots"
description: "APEX (Action Priors enable Efficient Exploration): a simple yet versatile imitation learning framework that integrates demonstrations directly into reinforcement learning (RL), maintaining high exploration while grounding behavior with expert-informed priors."
importance: 1
img : https://img.youtube.com/vi/f6GKpPCyOGY/hqdefault.jpg

category: work
related_publications: false
---

<!-- Embedded YouTube video -->
<iframe width="100%" height="400"
        src="https://www.youtube.com/embed/f6GKpPCyOGY"
        title="APEX Demo"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
</iframe>
---

Learning by imitation provides an effective way for robots to develop well-regulated complex behaviors and directly benefit from natural demonstrations. State-of-the-art imitation learning (IL) approaches typically leverage Adversarial Motion Priors (AMP), which, despite their impressive results, suffer from two key limitations. They are prone to mode collapse, which often leads to overfitting to the simulation environment and thus increased sim-to-real gap, and they struggle to learn diverse behaviors effectively. To overcome these limitations, we introduce APEX (Action Priors enable Efficient Exploration): a simple yet versatile imitation learning framework that integrates demonstrations directly into reinforcement learning (RL), maintaining high exploration while grounding behavior with expert-informed priors. We achieve this through a combination of decaying action priors, which initially bias exploration toward expert demonstrations but gradually allow the policy to explore independently. This is complemented by a multi-critic RL framework that effectively balances stylistic consistency with task performance. Our approach achieves sample-efficient imitation learning and enables the acquisition of diverse skills within a single policy. APEX generalizes to varying velocities and preserves reference-like styles across complex tasks such as navigating rough terrain and climbing stairs, utilizing only flat-terrain kinematic motion data as a prior. We validate our framework through extensive hardware experiments on the Unitree Go2 quadruped. There, APEX yields diverse and agile locomotion gaits, inherent gait transitions, and the highest reported speed for the platform to the best of our knowledge (
∼
4.5
⁢
m
/
s
 in sim-to-sim transfer, and a peak velocity of 
∼
3.3
⁢
m
/
s
 on hardware). Our results establish APEX as a compelling alternative to existing IL methods, offering better efficiency, adaptability, and real-world performance. Video link: https://youtu.be/f6GKpPCyOGY


---
layout: page
title: "Yoga Pose Estimation and Tracking"
description: ""
img: assets/img/yoga.png
importance: 1
category: work
related_publications: false
---



## Overview



This project aimed to develop a **real-time yoga pose detection and correction system** using **computer vision (CV) techniques and statistical modeling**. The system leveraged **MediaPipe and OpenCV** to capture and process image data for accurate **pose estimation, joint angle computation, and feedback generation**. Worked with [Prof. Kunal Korgaonkar](https://www.bits-pilani.ac.in/goa/kunal-kishore-korgaonkar/) in the CSIS Robotics Lab, BITS Goa. 
The approach involved **computing joint angles** from processed images, comparing them with predefined statistical ranges using **Z-score analysis**, and suggesting corrections to improve pose accuracy.

<div class="row">
    <div class="col-sm mt-3 mt-md-0" style="max-width: 50%; margin: auto;">
        {% include figure.liquid loading="eager" path="assets/img/yoga.png" title="example image" class="img-fluid rounded z-depth-1" style="width: 100%; max-width: 400px;" %}
    </div>
</div>

### **Project Contributions:**
- **Developed a real-time yoga pose tracking system** integrating depth sensors and computer vision techniques.
- **Implemented MediaPipe for rapid pose detection** and tracking using lightweight perception pipelines.
- **Extracted joint angles from processed images** and structured datasets for analysis.
- **Curated a statistical dataset** with **Z-distribution-based angle ranges** for each yoga pose.
- **Computed Z-scores** to compare real-time poses with mean values and assess deviation.
- **Designed feedback algorithms** to suggest pose corrections dynamically.
- **Confidence in pose measurements fall within natural biomechanical limits** across individuals.
- **Implemented confidence thresholds**:
  - **Minimum Detection Confidence:** Ensuring reliable pose identification.
  - **Maximum Tracking Confidence:** Maintaining robust real-time tracking.

### **Technical Highlights:**
- **MediaPipe Framework:** Enabled rapid prototyping and deployment of **computer vision pipelines**.
- **OpenCV for Image Processing:** Extracted skeletal features and computed pose angles.
- **Statistical Z-Score Analysis:** Compared joint angles to pre-defined pose accuracy thresholds.
- **Real-Time Pose Extraction & Classification:** Used 3D angle calculations to label poses dynamically.
- **Confidence Interval Computation:** Improved pose consistency across different individuals.
- **Error Handling & Adaptive Tuning:** Made the model resilient to **minor pose variations**.

<div class="row">
    <div class="col-sm mt-3 mt-md-0" style="max-width: 50%; margin: auto;">
        {% include figure.liquid loading="eager" path="assets/img/yoga_landmark.jpeg" title="example image" class="img-fluid rounded z-depth-1" style="width: 100%; max-width: 400px;" %}
         <div class="caption text-center">Detected Landmarks</div>
    </div>
</div>


### **Impact and Future Scope:**
This system enhances **yoga training, fitness applications, and physiotherapy** by providing **automated pose correction and feedback**. The work can be extended to:
- **Personalized AI-driven yoga assistants** with real-time coaching.
- **Rehabilitation & physiotherapy monitoring** for patient recovery.
- **Integration with Augmented Reality (AR)** for interactive fitness solutions.




<!-- ### **Repository & Additional Resources:** -->
**GitHub Repository and Project Report**: [Yoga Pose Detection System](https://github.com/laukik29/Machine-Learning-/tree/main/Motion%20Tracking)  






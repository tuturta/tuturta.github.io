---
layout: page
title: Robot Locomotion Learning with Imitation
description: Master Project (LIS) | 2024.02 - 2024.07
img: assets/img/il1.jpg
importance: 3
category: work
giscus_comments: false
---

Learning complex behaviors in high-dimensional action and state spaces, such as animal locomotion, is a major challenge in robotics. This project explores the use of **Imitation Learning (IL)** to train animal-shaped robots in the MuJoCo simulator by leveraging online videos of animals as expert demonstrations.  

We developed a **modular 3-stage pipeline** that integrates state-of-the-art techniques in 3D Pose Estimation, Motion Retargeting, and Adversarial Imitation Learning. First, animal poses are estimated from videos using **DeepLabCut (DLC)**. These poses are then reconstructed into 3D skeletons via triangulation with the **AcinoSet** framework. Finally, **spatio-temporal motion retargeting (STMR)** adapts the animal skeletons to match the robot’s morphology, producing feasible demonstrations for training with **Variational Adversarial Imitation Learning from Observation (VAILO)**.  

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/our_pipeline.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

The main challenge of this approach lies in the motion retargeting stage, where the pipeline must respect the robot’s physical constraints to ensure realistic and executable movements. This work provides insights into building **modular, robust pipelines** for transferring animal behavior to robotic systems, paving the way for more naturalistic and adaptive robot locomotion.  

For a detailed description of this project, you can access the [full PDF](/assets/pdf/il.pdf).

**Project Supervisor & Contact:**  
[Alexander Dittrich](mailto:alexander.dittrich@epfl.ch) – Doctoral Assistant, Laboratory of Intelligent System (LYS)

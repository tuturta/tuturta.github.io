---
layout: page
title: Autonomous Sensing in Polar Regions.
description: Master Thesis + Research Engineer (EERL) | 2025.03 - 2026.01
img: assets/img/eerl2.jpg
importance: 1
category: work
related_publications: false
---

Atmospheric aerosols — tiny particles suspended in the air — play a crucial role in Earth’s climate by influencing solar radiation and cloud formation. Yet, understanding their vertical distribution, especially in remote regions like the Arctic, remains a major challenge for accurate climate modeling. To tackle this, I contributed to the improvement of the [Modular Multiplatform Compatible Air System (MoMuCAMS)](https://amt.copernicus.org/articles/17/731/2024/) at the Extreme Environments Research Laboratory (EERL), a tethered-balloon platform designed for in situ measurements of aerosols and trace gases in the lower troposphere under harsh environmental conditions.

My work focused on making MoMuCAMS more autonomous and scalable. I designed and implemented the Winch AutoPilot Software (WAPS), which allows the tethered balloon to follow predefined flight programs while continuously monitoring safety parameters like high wind speeds, abnormal altitude loss, low battery voltage, and communication failures. Built in Python with a modular architecture and a Qt-based graphical interface, WAPS enables a single, non-expert user to safely operate the system.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/eerl1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Our tethered balloon system deployed by EERL Team during an arctic campaign
</div>

Because field validation in extreme environments is challenging, I developed a Pybullet-based simulator to assess autopilot performance and robustness with realistic live data.

This work lays the foundation for autonomous, distributed deployments of MoMuCAMS, with upcoming campaigns at [Greenfjord](https://greenfjord-project.ch/) and the [Tara Polar Station (TPS)](https://fondationtaraocean.org/goelette/tara-polar-station/) expedition. Future developments aim to incorporate real-time cloud and temperature inversion detection, allowing dynamic adjustment of flight profiles and further reducing operator intervention.

For a detailed description of the project, you can access my [Master’s thesis PDF](/assets/pdf/thesis.pdf).

**Project Supervisor & Contact:**  
[Pr. Julia Schmale](mailto:julia.schmale@epfl.ch) – Assistant Professor, Extreme Environmental Research Laboratory (EERL)   
[Dr. Roman Pohorsky](mailto:roman.pohorsky@epfl.ch) – Postdoctoral Researcher, Extreme Environmental Research Laboratory (EERL)
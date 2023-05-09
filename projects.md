---
layout: page
title: Projects
permalink: /projects/
---

# Stealth System
*Individual capstone project chosen for "Game Engine Architecture" course*

{% include chip.html tag="C++" %} {% include chip.html tag="Collision Detection" %} {% include chip.html tag="Nav Mesh & AI" %} {% include chip.html tag="Third-person" %}

<video muted autoplay loop controlslist="nodownload"
    class="container-mb" width="100%">
    <source src="/media/StealthSystemDemo.mp4" type="video/mp4">
</video>

<video muted autoplay loop controlslist="nodownload"
    class="container-mb" width="100%">
    <source src="/media/NavMeshDemo.mp4" type="video/mp4">
</video>

![](/media/StealthDetectionSM.png)

<!-- <video muted autoplay loop controlslist="nodownload"
    class="container-mb" width="100%">
    <source src="/media/RootMotionDemo.mp4" type="video/mp4">
</video> -->

Features developed:
 - **Player Controller & Cover System:** Design API to detect valid reachable covers by turn/sneak maneuvers using neighbor search and backface culling tests.
 - **Nav Mesh & AI:** Develop an automatic nav mesh generation pipeline for orthogonal level layout using contour/polygon generation and edge-graph formulation. Implement A* with funnel smoothing for effective NPC behavior.
 - **NPCs & Stealth Detection:** Represent NPCs with view cones and analog detection meter that fills/decays based on visibility of player's key body parts. Design state machine interaction for seeking last known player location based on detection thresholds.
 - **Collision Detection:** Implement collision tests for spheres, boxes, rays, cones and planes to support stealth gameplay features.

<BR>
<HR>

# Sci-Fi Spaceship Controller
*On-going passion project, inspired by the Banshee from the Halo series*

{% include chip.html tag="C#" %} {% include chip.html tag="Spaceship Controller" %} {% include chip.html tag="Follow Camera" %}

<iframe class="container-mb container-video" width="100%" frameborder="0" allow="autoplay" src="https://www.youtube.com/embed/vKb3PywNiMI?mute=1&rel=0&modestbranding=1" allowfullscreen></iframe>

Work done in current phase:
 - Programmed controller with ability to boost, turn, drift, and perform **evasive maneuvers**.
 - Implemented **modular "smooth follow" component** for third-person camera.
 - Added **motion-based tilt** (roll) to achieve the right "feel".

Work planned for next phase:
 - Support for complex kinematics such as partial damage, knockback from collisions, etc.
 - Expanded terrain and particle effects for exhaust

<BR>
<HR>

# VR Research Volunteer

*Exploring new user interactions beyond 2D menus*

{% include chip.html tag="C#" %} {% include chip.html tag="Unity" %} {% include chip.html tag="Oculus" %}

![VR Spatial Interaction Teaser](/media/VRDemo.jpg)

Working part-time under a PhD student as an engineer to help improve interactions in XR.
 - Port input controller from device-based to <a target="_blank" href="https://github.com/powenyao/XR-Interaction-Toolkit-Examples/wiki/Design:-Locomotion-System">action-based system</a>
 - Implemented <a target="_blank" href="https://github.com/powenyao/XR-Interaction-Toolkit-Examples/wiki/Design:-Controller-Manager">state machine and input manager</a> for customizable locomotion
 - Helped develop a demo for submission to <a target="_blank" href="https://s2023.siggraph.org/program/immersive-pavilion/">SIGGRAPH 2023</a>

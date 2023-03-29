---
layout: page
title: Projects
permalink: /projects/
---

# Game Engine Development
*Implementing new features on reference engine (ongoing coursework)*
  
{% include chip.html tag="C++" %} {% include chip.html tag="3D Math" %} {% include chip.html tag="Linear Algebra" %}

Features worked on:
 - **View frustum culling** based on OBB tests with FOV planes
 - Basic physics thread with **collision detection** for sphere and box colliders


# Atmospheric Flying Game
*On-going passion project, inspired by the Banshee from the Halo series*

{% include chip.html tag="C#" %} {% include chip.html tag="Spaceship Controller" %} {% include chip.html tag="Third-Person Camera" %}

<iframe class="video-container" width="100%" frameborder="0" allow="autoplay" src="https://www.youtube.com/embed/vKb3PywNiMI?mute=1&rel=0" allowfullscreen></iframe>

Work done in current phase:
 - Programmed controller with ability to boost, turn, drift, and perform **evasive maneuvers**.
 - Implemented **modular "smooth follow" component** for third-person camera.
 - Added **motion-based tilt** (roll) to achieve the right "feel".

Work planned for next phase:
 - Support for complex kinematics such as partial damage, knockback from collisions, etc.
 - Expanded terrain and particle effects for exhaust

# VR Research Volunteer

*Exploring new user interactions beyond 2D menus*

{% include chip.html tag="C#" %} {% include chip.html tag="Unity" %} {% include chip.html tag="Oculus" %}

![VR Spatial Interaction Teaser](/media/VRDemo.jpg)

Working part-time under a PhD student as an engineer to help improve interactions in XR.
 - Port input controller from device-based to <a target="_blank" href="https://github.com/powenyao/XR-Interaction-Toolkit-Examples/wiki/Design:-Locomotion-System">action-based system</a>
 - Implemented <a target="_blank" href="https://github.com/powenyao/XR-Interaction-Toolkit-Examples/wiki/Design:-Controller-Manager">state machine and input manager</a> for customizable locomotion
 - Helped develop a demo for submission to <a target="_blank" href="https://s2023.siggraph.org/program/immersive-pavilion/">SIGGRAPH 2023</a>

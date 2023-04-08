---
layout: page
title: Projects
permalink: /projects/
---

# Game Engine Development
*Implementing new features on reference engine (ongoing coursework)*
  
{% include chip.html tag="C++" %} {% include chip.html tag="3D Math" %} {% include chip.html tag="Collision Detection" %} {% include chip.html tag="Animation FSM" %}

<!-- <iframe class="container-mb container-video" width="100%" frameborder="0" src="https://www.youtube.com/embed/J__xEZApP_M?rel=0&controls=0&disablekb=1&fs=0&mute=1&playlist=J__xEZApP_M&autoplay=1&&loop=1&modestbranding=1"></iframe> -->

<video muted controls autoplay loop controlslist="nodownload"
    class="container-mb" width="100%">
    <source src="/media/RootMotionDemo.mp4" type="video/mp4">
</video>

Features worked on:
 - Third-person controller with **cover system** (inspired by stealth games like Splinter Cell)
 - Ability to **extract root motion** and transfer to physics controller
 - **View frustum culling** based on OBB tests with FOV planes
 - Basic physics thread with **collision detection** for sphere and box colliders

# Sci-Fi Spaceship Controller
*On-going passion project, inspired by the Banshee from the Halo series*

{% include chip.html tag="C#" %} {% include chip.html tag="Spaceship Controller" %} {% include chip.html tag="Third-Person Camera" %}

<iframe class="container-mb container-video" width="100%" frameborder="0" allow="autoplay" src="https://www.youtube.com/embed/vKb3PywNiMI?mute=1&rel=0&modestbranding=1" allowfullscreen></iframe>

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

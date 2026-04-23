---
layout: page
title: Stealth Gameplay Systems
permalink: /stealth-system-project/
carousels:
 - images:
   - image: /media/AlterEgo.png
   - image: /media/SpellCrafter.png
   - image: /media/stealth4.gif
---

I designed a detailed stealth system for the individual capstone project of my Game Engine Architecture course. Below, I've documented some key development aspects from this rigorous six-week journey.

Games that inspired this project: [Splinter Cell](https://en.wikipedia.org/wiki/Tom_Clancy%27s_Splinter_Cell), [Mark of the Ninja](https://www.klei.com/games/mark-ninja), [Volume](https://store.steampowered.com/app/365770/Volume/)

# AI: Nav Mesh Generation & Path Finding

 - Developed a pipeline to process level geometry into nav mesh graph for NPC pathfinding.
 - Algorithms: Contour detection for orthogonal polygons, connected components, A*, funnel smoothing

{% include carousel.html height="50" unit="%" duration="7" number="1" %}

# NPC Behavior and Detection

 - Implemented NPCs with view cones and behavior state machine using analog "detection meter" based on visibility of key player body parts.

# Cover System

## Third-Person Controller and Animation

 - Extended existing animation code to support root motion extraction and transfer to physics controller.
 - Implemented player controller with follow-camera, cover interaction, and animation FSM.

<video muted controls autoplay loop controlslist="nodownload"
    class="container-mb" width="100%">
    <source src="/media/RootMotionDemo.mp4" type="video/mp4">
</video>

## Cover System


## AI: NPC behavior

 - Stealth view cones

## Learnings

 - Technical debt aspects
 - It's okay to discard and redo your own work

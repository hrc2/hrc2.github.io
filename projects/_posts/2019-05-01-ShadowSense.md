---
layout: project
title: "ShadowSense - Detecting Human Touch in a Social Robot"
image: /assets/images/projects/shadowsense.jpg
category: projects
published: true
tags: [design]
---
{% include JB/setup %}

ShadowSense is a low-tech, low-cost touch sensing method to recognize touch gestures and touch positions on social robots in the hope of improving the robot’s awareness and promoting intelligent interaction behaviors. 


<!--more-->

**Collaborators: Yuhan Hu, Sara Bejarano, Guy Hoffman, Emilie Baker, Kirstin Petersen, Hadas Kress-Gazit, Christina Chang, and Jijie Zhou (Cornell).**

<iframe width="560" height="315" src="https://www.youtube.com/embed/Jr4b6qaK4fg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

A camera inside a robot’s body captures the shadows created by touching its skin, or even hovering over the skin, detecting both touch positions and social gestures. We use a a Densely Connected Convolutional Neural Network to recognize touch gestures from shadow images. In an experiment, we evaluated six interaction gestures: a palm touch, punch, two hands, hug, point, and nothing. The classifier was evaluated with three lighting conditions: daylight, dusk, and night. The results showed high accuracy in gesture recognition, between 87.5% and 96.0%, dependent on the lighting. 


ShadowSense could provide a privacy-maintaining alternative to camera-based interaction with social home robots. By physically covering the robot’s eyes with a translucent material, as some users already do with their laptop cameras, a robot can still make use of some interaction data in the form of user’s shadows instead of high-fidelity images.


ShadowSense is a collaborative project with Cornell Collective Embodied Intelligence Lab, and Verifiable Robotics Research Group. The research was supported under NSF National Robotic Initiative Award NRI:1830471.



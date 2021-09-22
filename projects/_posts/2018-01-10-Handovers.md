---
layout: project
title: "Human-Robot Object Handovers"
image: /assets/images/projects/handover-project-2020.png
category: projects
published: true
tags: [control, studies]
---
{% include JB/setup %}

In this project, we investigate the collaborative task of object handovers between a human and a robot from a number of perspectives: formal controller synthesis, user studies, and reinforcement learning. 

<!--more-->

Object handovers are a central aspect of human-robot collaboration in both industrial and domestic environments. Tasks such as surgical assistance, housekeeping, rehabilitation assistance, eldercare, warehousing, and collaborative assembly require robots to give objects to humans and/or take objects from humans. Object handovers are challenging for robots as they involve coordination in both time and space of hand movements, grip forces, body postures, and non-verbal cues like gazes and pointing gestures. This project explores three research directions: First, we tackle the challenge of designing robot controllers to address various scenarios of human-robot handovers. Second, we investigate how a robot can use non-verbal cues to improve the human's experience and fluency of human-robot handovers. Third, we seek to provide new insights on human behavior and preferences in human-human and human-robot handovers.

**Collaborators: Alap Kshirsagar (Cornell), Melanie Lim (Cornell), Shemar Christian (Cornell), Tair Sela (BGU), Rahul Raji (Cornell), Yael Edan (BGU), Armin Biess (BGU), Hadas Kress-Gazit (Cornell), and Guy Hoffman (Cornell).**


## Specifying and Synthesizing Human-Robot Object Handovers

In this project, we investigate human-robot handover controllers that are automatically synthesized from high-level specifications. In contrast to existing controllers, this approach can provide formal guarantees on the timing of each of the handover phases. Using synthesis also allows end-users to specify and dynamically change the robot's behaviors using high-level requirements of goals and constraints rather than by tuning low-level controller parameters. 

**Publication:** A. Kshirsagar, H. Kress-Gazit, and G. Hoffman, <a href="https://ieeexplore.ieee.org/document/8967709">"Specifying and Synthesizing Human-Robot Handovers"</a>, IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Macau, 4-8 November 2019.

<iframe width="560" height="315" src="https://www.youtube.com/embed/zfGxSXAFWyc" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## Gaze Behaviors in Human-Robot Handovers

This project investigates gaze behaviors of a robot receiving an object from a human. Robot gaze is an important nonverbal behavior during human-robot handovers, yet prior work has only studied robots as givers. We analyze videos and human participant studies to make design recommendations for how to program a receiver robot's social gaze. 

**Publication:** A. Kshirsagar, M. Lim, S. Christian and G. Hoffman, <a href="https://ieeexplore.ieee.org/document/9165096">"Robot Gaze Behaviors in Human-to-Robot Handovers"</a>, IEEE Robotics and Automation Letters 5(4):6552-6558, 2020.

<iframe width="560" height="315" src="https://www.youtube.com/embed/eW6IvZKLrlQ
" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## Evaluating Guided Policy Search for Human-Robot Handovers

This project studies model-based reinforcement learning (RL) to train a robot controller for human-robot object handovers. RL is a promising approach to develop handover policies, but existing methods did not consider important aspects of human-robot handovers, namely large spatial variations in reach locations, moving targets, and generalizing over mass changes induced by the object being handed over. We report on promising benefits, but also limitations of existing RL methods for this HRI task.

*Publication:* A. Kshirsagar, G. Hoffman, A. Biess, <a href="https://ieeexplore.ieee.org/document/9381633">"Evaluating Guided Policy Search for Human-Robot Handovers"</a>, IEEE Robotics and Automation Letters 6 (2) : 3933-3940, 2021.

<iframe width="560" height="315" src="https://www.youtube.com/embed/8Y5w-gidfr4" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

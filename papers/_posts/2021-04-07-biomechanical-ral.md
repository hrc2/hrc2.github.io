---
layout: paper
title: "Biomechanical Motion Planning for a Wearable Robotic Forearm"
year: 2021
shortref: "Vatsal & Hoffman RAL 2021"
shorttitle: "Biomechanical Motion Planning for a Wearable Robotic Forearm"
nickname: biomechanical-ral
journal: "IEEE Robotics and Automation Letters"
volume: 6
issue: 3
pages: 5024–5031
authors: "Vatsal, V., and Hoffman, G."
image: biomechanical-ral.png
pdf: VatsalHoffmanRAL21.pdf
pdflink:
fulltext:  
pubtype: journal
github:
pmid:  
pmcid:
f1000:
figshare:
doi: 10.1109/LRA.2021.3071675
category: papers
published: true
tags: [biomechanics, motion planning]
---
{% include JB/setup %}

# Abstract

Supernumerary robotic devices in the form of wearable arms enhance a user's reachable workspace and provide them with additional capabilities. However, the user may experience considerable force and moment loads on their body due to the robot's motion. In this letter, we present a simulation and trajectory planning framework that aims to minimize the load on a user's muscles while operating a Wearable Robotic Forearm (WRF). Using a high-fidelity model of the human arm, we construct a term for biomechanical costs that is subsequently added to the overall cost function for a motion planner. For evaluation, the planner is initialized with shortest paths linearly interpolated between ten start and goal state pairs in the configuration space, as well as with paths optimized for reaction moments using a local search. We find that the biomechanical planner coupled with locally-optimized initialization reduces mean human muscle fiber forces by up to 23.47% compared to the linearly interpolated trajectories.

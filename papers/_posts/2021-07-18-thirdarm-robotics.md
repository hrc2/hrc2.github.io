---
layout: paper
title: "The Wearable Robotic Forearm: Design and Predictive Control of a Collaborative Supernumerary Robot"
year: 2021
shortref: "Vatsal & Hoffman. Robotics 2021"
shorttitle: "The Wearable Robotic Forearm"
nickname: thirdarm-robotics
journal: "Robotics"
volume: 10
issue: 3
pages: 19
authors: "Vatsal, V., & Hoffman, G."
image: thirdarm-robotics.jpg
pdf: VatsalHoffmanRobotics21.pdf
pdflink:  
fulltext: https://www.mdpi.com/2218-6581/10/3/91
pubtype: journal
github: 
pmid:  
pmcid: 
f1000: 
figshare: 
doi: 10.3390/robotics10030091
category: papers
published: true
tags:
- wearable, design, controls
---
{% include JB/setup %}

# Abstract 

This article presents the design process of a supernumerary wearable robotic forearm (WRF), along with methods for stabilizing the robot’s end-effector using human motion prediction. The device acts as a lightweight “third arm” for the user, extending their reach during handovers and manipulation in close-range collaborative activities. It was developed iteratively, following a user-centered design process that included an online survey, contextual inquiry, and an in-person usability study. Simulations show that the WRF significantly enhances a wearer’s reachable workspace volume, while remaining within biomechanical ergonomic load limits during typical usage scenarios. While operating the device in such scenarios, the user introduces disturbances in its pose due to their body movements. We present two methods to overcome these disturbances: autoregressive (AR) time series and a recurrent neural network (RNN). These models were used for forecasting the wearer’s body movements to compensate for disturbances, with prediction horizons determined through linear system identification. The models were trained offline on a subset of the KIT Human Motion Database, and tested in five usage scenarios to keep the 3D pose of the WRF’s end-effector static. The addition of the predictive models reduced the end-effector position errors by up to 26% compared to direct feedback control. 

This work was supported by the National Science Foundation (NSF) under NRI Award No. 1734399.

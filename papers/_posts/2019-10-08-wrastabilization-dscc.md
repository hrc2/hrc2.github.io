---
layout: paper
title: "End-Effector Stabilization of a Wearable Robotic Arm Using Time Series Modeling of Human Disturbances"
year: 2019
shortref: "Vatsal & Hoffman. DSCC 2019"
shorttitle: "End-Effector Stabilization of a Wearable Robotic Arm Using Time Series Modeling of Human Disturbances"
nickname: wrastabilization-dscc
journal: "ASME Dynamic Systems and Control Conference"
volume:
issue:
pages:
authors: "Vatsal, V. & Hoffman, G."
image: wearable-arm-dscc.png
pdf: VatsalHoffmanDSCC19.pdf
pdflink:
fulltext:  
pubtype: conference
github:
pmid:  
pmcid:
f1000:
figshare:
doi:
category: papers
published: true
tags: [stabilization, dynamics]
---
{% include JB/setup %}

# Abstract

For a wearable robotic arm to autonomously assist a human, it has to be able to stabilize its end-effector in light of the human’s independent activities. This paper presents a method for stabilizing the end-effector in planar assembly and pick-and-place tasks. Ideally, given an accurate positioning of the end effector and the wearable robot attachment point, human disturbances could be compensated by using a simple feedback control strategy. Realistically, system delays in both sensing and actuation suggest a predictive approach. In this work, we characterize the actuators of a wearable robotic arm and estimate these delays using linear models. We then consider the motion of the human arm as an autoregressive process to predict the deviation in the robot’s base position at a time horizon equivalent to the estimated delay. Generating set points for the end-effector using this predictive model, we report reduced position errors of 19.4% (x) and 20.1% (y) compared to a feedback control strategy without prediction.

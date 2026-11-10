---
layout: paper
title: "Performing Human Shadow Detection for Camera-Based Privacy-Preserving Human-Robot Interactions"
year: 2024
shortref: "Hu et al. RO-MAN 2024"
shorttitle: "Human Shadow Detection for Privacy-Preserving HRI"
nickname: shadow-detection-privacy
journal: "Proceedings of the 2024 33rd IEEE International Conference on Robot and Human Interactive Communication (RO-MAN)"
volume:
issue:
pages: 1013-1020
authors: "Hu, Y., Ray, P., & Hoffman, G."
image: shadow-detection-privacy.jpg
summary: "A semi-transparent camera layer and a retrained EfficientNet let a robot detect and track people from their shadows alone, preserving privacy while still enabling real-time gaze-based interaction."
pdf: HuetalROMAN24.pdf
pdflink:
fulltext:
pubtype: conference
github:
pmid:
pmcid:
f1000:
figshare:
doi: 10.1109/ro-man60168.2024.10731324
category: papers
published: true
award:
tags: [studies, ai]
projects: [privacy-hri]
---
{% include JB/setup %}

# Abstract

Home robots are envisioned to provide in-home assistance for older adults and other people who may need help with daily tasks. To gather information for inferring user status, robots typically require cameras to detect human subjects, track their positions, and recognize their activities or poses. However, having cameras in personal spaces, such as homes, could pose privacy concerns and risks due to the potential misuse or compromise of personal image data. It can also lead to psychological unease and feelings of insecurity, stemming from the fear of being watched and recorded. To address this issue, this paper proposes a method for preserving privacy based on physically obstructing the robot's camera image and computer vision methods for detection and tracking of humans in these obstructed images. We present a hardware platform that includes a semi-transparent physical layer in front of the robot's cameras to obtain privacy-preserving shadow images, and a software framework that uses a pre-trained EfficientNet, retrained with a newly-collected dataset of human shadow images for detecting and tracking human subjects. The testing results reveal that the network achieves reliable accuracy in detecting humans from various distances and angles, and it can be applied to a new subject that it has never seen before. Finally, the algorithm is implemented in a gaze-based human-robot interaction scenario, demonstrating its ability to track humans in real time while preserving privacy.

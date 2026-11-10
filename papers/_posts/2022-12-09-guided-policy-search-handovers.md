---
layout: paper
title: "Lessons Learned from Utilizing Guided Policy Search for Human-Robot Handovers with a Collaborative Robot"
year: 2022
shortref: "Kshirsagar et al. RAAI 2022"
shorttitle: "Guided Policy Search for Handovers"
nickname: guided-policy-search-handovers
journal: "Proceedings of the 2022 2nd International Conference on Robotics, Automation and Artificial Intelligence (RAAI)"
volume:
issue:
pages: 52-57
authors: "Kshirsagar, A., Faibish, T., Hoffman, G., & Biess, A."
image: guided-policy-search-handovers.jpg
summary: "Replicating a simulated Guided Policy Search result on a real collaborative-robot arm reveals it doesn't transfer cleanly: the workspace must shrink sharply, and the policy still errs badly on moving targets."
pdf: KshirsagaretalICRAAI22.pdf
pdflink:
fulltext:
pubtype: conference
github:
pmid:
pmcid:
f1000:
figshare:
doi: 10.1109/raai56146.2022.10092989
category: papers
published: true
award:
tags: [handovers, reinforcement learning]
projects: [handovers]
---
{% include JB/setup %}

# Abstract

We evaluate the performance of Guided Policy Search (GPS), a model-based reinforcement learning method, for generating the handover reaching motions of a collaborative robot arm. In a previous work, we evaluated GPS for the same task but only in a simulated environment. This paper provides a replication of the findings in simulation, along with new insights on GPS when used on a physical robot platform. First, we find that a policy learned in simulation does not transfer readily to the physical robot due to differences in model parameters and existing safety constraints on the real robot. Second, in order to successfully train a GPS model, the robot's workspace needs to be severely reduced, owing to the joint-space limitations of the physical robot. Third, a policy trained with moving targets results in large worst-case errors even in regions spatially close to the training target locations. Our findings motivate further research towards utilizing GPS in human-robot interaction settings, especially where safety constraints are imposed.

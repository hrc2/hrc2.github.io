---
layout: paper
title: "Active Attention-Modified Policy Shaping"
year: 2019
shortref: "Kessler Faulkner et al. AAMAS 2019"
shorttitle: "Active Attention-Modified Policy Shaping"
nickname: aamps-aamas
journal: "International Conference on Autonomous Agents and Multiagent Systems (AAMAS)"
volume:
issue:
pages: 
authors: "Kessler Faulkner, T., Gutierrez, R., Schaertl Short, E., Hoffman, G., & Thomaz, A."
image: aamps-robot.jpg
pdf: KesslerFaulkneretalAAMAS19.pdf
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
award: 
tags: [ai, mdp]
---
{% include JB/setup %}

# Abstract

We present the Active Attention-Modified Policy Shaping (Active AMPS) algorithm, which allows learning robots to request feed- back from multi-tasking human teachers. Active AMPS uses Re- inforcement Learning supplemented with feedback from teachers, while avoiding frequently interrupting the teacher. This algorithm does so by selectively asking for attention from teachers in low- information areas of the state space when there is uncertainty about the teacher’s feedback. Active AMPS allows people to take breaks from teaching the robot to complete other tasks, and is forgiving to lapses in human attention if learning occurs over long periods of time. We test Active AMPS both in simulation and on a physical robot in a human study. In simulation, we find that Active AMPS outperforms Attention-Modified Policy Shaping (AMPS), achieving an 11.0% increase in area under its learning curve while receiving 89.9% less feedback. In the human study, we find statistically signif- icant results showing that Active AMPS allows people to complete 77.5% more work than AMPS while the robot receives 48.5% less feedback, without decreasing performance.
---
layout: paper
title: "Collaboration in Human-Robot Teams"
year: 2004
shortref: "Hoffman & Breazeal AIAA 2004"
shorttitle: "Collaboration in Human-Robot Teams"
nickname: collaboration-aiaa
journal: "AIAA 1st Intelligent Systems Technical Conference"
volume: 
issue: 
pages: 
authors: "Hoffman, G. & Breazeal, C."
image: leobuttons.jpg
pdf: HoffmanBreazealAIAA04.pdf
pdflink:
fulltext: 
pubtype: conference
github: 
pmid:  
pmcid: 
f1000: 
figshare: 
doi: 10.2514/6.2004-6434
category: papers
published: true
award: Best Session Paper
tags: [collaboration,ai]
---
{% include JB/setup %}

# Abstract 

Many new applications for robots require them to work alongside people as capable members of human-robot teams. These include—in the long term—robots for homes, hospitals, and offices, but already exist in more advanced settings, such as space exploration. The work reported in this paper is part of an ongoing collaboration with NASA JSC to develop Robonaut, a humanoid robot envisioned to work with human astronauts on maintenance operations for space missions. To date, work with Robonaut has mainly investigated performing a joint task with a human in which the robot is being teleoperated. However, perceptive disorientation, sensory noise, and control delays make teleoperation cognitively exhausting even for a highly skilled operator. Control delays in long range teleoperation also make shoulder-to-shoulder teamwork difficult. These issues motivate our work to make robots collaborating with people more autonomous.
Our work focuses on a scenario of a human and an autonomous humanoid robot working together shoulder-to-shoulder, sharing the workspace and the objects required to complete a task. A robotic member of such a team must be able to work towards a shared goal, and be in agreement with the human as to the sequence of actions that will be required to reach that goal, as well as dynamically adjust its plan according to the human’s actions. Human-robot collaboration of this nature is an important yet relatively unexplored kind of human-robot interaction.
This paper describes our work towards building a dynamic collaborative framework enabling such an interaction. We discuss our architecture and its implementation for controlling a humanoid robot, working on a task with a human partner. Our approach stems from Joint Intention Theory, which shows that for joint action to emerge, teammates must communicate to maintain a set of shared beliefs and to coordinate their actions towards the shared plan. In addition, they must demonstrate commitment to doing their own part, to the others doing theirs, to providing mutual support, and finally—to a mutual belief as to the state of the task.
We argue that to this end, the concept of task and action goals is central. We therefore present a goal-driven hierarchical task representation, and a resulting collaborative turn-taking system, implementing many of the above-mentioned requirements of a robotic teammate. Additionally, we show the implementation of relevant social skills supporting our collaborative framework.
Finally, we present a demonstration of our system for collaborative execution of a hierarchical object manipulation task by a robot-human team. Our humanoid robot is able to divide the task between the participants while taking into consideration the collaborator’s actions when deciding what to do next. It is capable of asking for mutual support in the cases where it is unable to perform a certain action. To facilitate this interaction, the robot actively maintains a clear and intuitive channel of communication to synchronize goals, task states, and actions, resulting in a fluid, efficient collaboration.
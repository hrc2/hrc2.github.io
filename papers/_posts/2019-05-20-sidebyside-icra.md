---
layout: paper
title: "SMT-Based Control and Feedback for Social Navigation"
year: 2019
shortref: "Campos et al. ICRA 2019"
shorttitle: "SMT-Based Control and Feedback for Social Navigation"
nickname: sidebyside-icra
journal: "IEEE International Conference on Robotics and Automation (ICRA)"
volume:
issue:
pages: 
authors: "Campos, T., Pacheck, A., Hoffman, G., & Kress-Gazit, H."
image: side-by-side-smt.jpg
pdf: CamposetalICRA19.pdf
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
tags: [ai, formalmethods]
---
{% include JB/setup %}

# Abstract

This paper combines techniques from Formal Methods and Human-Robot Interaction (HRI) to address the challenge of a robot walking with a human while maintaining a socially acceptable distance and avoiding collisions. We formulate a set of constraints on the robot motion using Satisfiability Modulo Theories (SMT) formulas, and synthesize robot control that is guaranteed to be safe and correct. Due to its use of high-level formal specifications, the controller is able to provide feedback to the user in situations where human behavior causes the robot to fail. This feedback allows the human to adjust their behavior and recover joint navigation. We demonstrate the behavior of the robot in a variety of simulated scenarios and compare it to utility-based side-by-side navigation control.
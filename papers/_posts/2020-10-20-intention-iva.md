---
layout: paper
title: "Design Intention Inference for Virtual Co-Design Agents"
year: 2020
shortref: "Law et al. IVA 2020"
shorttitle: "Design Intention Inference for Virtual Co-Design Agents"
nickname: intention-iva
journal: "20th ACM International Conference on Intelligent Virtual Agents (IVA'20)"
volume: 
issue: 
pages:
authors: "Law, M. V., Kwatra, A., Dhawan, N., Einhorn, M., Rajesh, A. & Hoffman, G."
image: distopia-iva.png
pdf: LawetalIVA2020.pdf
pdflink:
fulltext:
pubtype: conference
github:
pmid:
pmcid:
f1000:
figshare:
doi: 10.1145/3383652.3423861
category: papers
published: true
tags: [Human-AI co-design, Intention recognition, Design agents]
---
{% include JB/setup %}

# Abstract

We address the challenge of inferring the design intentions of a human by an intelligent virtual agent that collaborates with the human. First, we propose a dynamic Bayesian network model that relates design intentions, objectives, and solutions during a human's exploration of a problem space. We then train the model on design behaviors generated by a search agent and use the model parameters to infer the design intentions in a test set of real human behaviors. We find that our model is able to infer the exact intentions across three objectives associated with a sequence of design outcomes 31.3% of the time. Inference accuracy is 50.9% for the top two predictions and 67.2% for the top three predictions. For any singular intention over an objective, the model's mean F1-score is 0.719. This provides a reasonable foundation for an intelligent virtual agent to infer design intentions purely from design outcomes toward establishing joint intentions with a human designer. These results also shed light on the potential benefits and pitfalls in using simulated data to train a model for human design intentions.
---
layout: paper
title: "Inferring Human Intent and Predicting Human Action in Human–Robot Collaboration"
year: 2024
shortref: "Hoffman et al. Annual Review of CRAS 2024"
shorttitle: "Inferring Human Intent and Predicting Human Action in HRC"
nickname: inferring-human-intent-review
journal: "Annual Review of Control, Robotics, and Autonomous Systems"
volume: 7
issue: 1
pages: 73-95
authors: "Hoffman, G., Bhattacharjee, T., & Nikolaidis, S."
image: inferring-human-intent-review.jpg
summary: "This review finds human-robot collaboration research mostly infers intent via Bayesian/MDP models or supervised learning, but still struggles with long-horizon predictions and realistic models of how humans adapt."
pdf: HoffmanetalAR24.pdf
pdflink:
fulltext:
pubtype: journal
github:
pmid:
pmcid:
f1000:
figshare:
doi: 10.1146/annurev-control-071223-105834
category: papers
published: true
award:
tags: [collaboration, ai, review]
projects: [lbm-failures]
---
{% include JB/setup %}

# Abstract

Researchers in human–robot collaboration have extensively studied methods for inferring human intentions and predicting their actions, as this is an important precursor for robots to provide useful assistance. We review contemporary methods for intention inference and human activity prediction. Our survey finds that intentions and goals are often inferred via Bayesian posterior estimation and Markov decision processes that model internal human states as unobserved variables or represent both agents in a shared probabilistic framework. An alternative approach is to use neural networks and other supervised learning approaches to directly map observable outcomes to intentions and to make predictions about future human activity based on past observations. That said, due to the complexity of human intentions, existing work usually reasons about limited domains, makes unrealistic simplifications about intentions, and is mostly constrained to short-term predictions. This state of the art provides opportunity for future research that could include more nuanced models of intents, reason over longer horizons, and account for the human tendency to adapt.

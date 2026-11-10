---
layout: paper
title: "Face2Gesture: Translating Facial Expressions into Robot Movements through Shared Latent Space Neural Networks"
year: 2024
shortref: "Suguitan et al. THRI 2024"
shorttitle: "Face2Gesture"
nickname: face2gesture
journal: "ACM Transactions on Human-Robot Interaction"
volume: 13
issue: 3
pages: 1-18
authors: "Suguitan, M., DePalma, N., Hoffman, G., & Hodgins, J."
image: face2gesture.jpg
summary: "A shared latent-space autoencoder lets a robot translate a person's facial expression directly into a newly generated, affectively matching movement, instead of picking from a fixed library."
pdf: SuguitanTHRI24.pdf
pdflink:
fulltext:
pubtype: journal
github:
pmid:
pmcid:
f1000:
figshare:
doi: 10.1145/3623386
category: papers
published: true
award:
tags: [social robot, design, ai]
projects: [telepresence]
---
{% include JB/setup %}

# Abstract

In this work, we present a method for personalizing human-robot interaction by using emotive facial expressions to generate affective robot movements. Movement is an important medium for robots to communicate affective states, but the expertise and time required to craft new robot movements promotes a reliance on fixed preprogrammed behaviors. Enabling robots to respond to multimodal user input with newly generated movements could stave off staleness of interaction and convey a deeper degree of affective understanding than current retrieval-based methods. We use autoencoder neural networks to compress robot movement data and facial expression images into a shared latent embedding space. Then, we use a reconstruction loss to generate movements from these embeddings and triplet loss to align the embeddings by emotion classes rather than data modality. To subjectively evaluate our method, we conducted a user survey and found that generated happy and sad movements could be matched to their source face images. However, angry movements were most often mismatched to sad images. This multimodal data-driven generative method can expand an interactive agent's behavior library and could be adopted for other multimodal affective applications.

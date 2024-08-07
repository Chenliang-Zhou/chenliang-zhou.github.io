---
title: "XQSV: A Structurally Variable Network to Imitate Human Play in Xiangqi"
collection: publications
permalink: /publications/2024-xiangqi
date: 2024-08-05
venue: 'IEEE CoG'
# link: 'https://aispace2.github.io/AISpace2/'
pdf: 'https://arxiv.org/abs/2407.04678'
# code: 'https://github.com/aispace2/aispace2'
teaser: '../images/2024-xiangqi.png'
authors: '<b>Chenliang Zhou</b>'
---

In this paper, we introduce an innovative deep learning architecture, termed *Xiangqi Structurally Variable (XQSV)*, designed to emulate the behavioral patterns of human players in Xiangqi, or Chinese Chess. The unique attribute of XQSV is its capacity to alter its structural configuration dynamically, optimizing performance for the task based on the particular subset of data on which it is trained. We have incorporated several design improvements to significantly enhance the network's predictive accuracy, including a local illegal move filter, an Elo range partitioning, a sequential one-dimensional input, and a simulation of imperfect memory capacity. Empirical evaluations reveal that XQSV attains a predictive accuracy of approximately 40%, with its performance peaking within the trained Elo range. This indicates the model's success in mimicking the play behavior of individuals within that specific range. A three-terminal Turing Test was employed to demonstrate that the XQSV model imitates human behavior more accurately than conventional Xiangqi engines, rendering it indistinguishable from actual human opponents. Given the inherent nondeterminism in human gameplay, we propose two supplementary relaxed evaluation metrics. To our knowledge, XQSV represents the first model to mimic Xiangqi players.

---
title: "FrePolad: Frequency-Rectified Point Latent Diffusion for Point Cloud Generation"
collection: publications
permalink:
date: 2024-09-20
venue: 'ECCV'
link: 'https://chenliang-zhou.github.io/FrePolad/'
pdf: 'https://arxiv.org/abs/2311.12090'
code: 'https://github.com/Chenliang-Zhou/FrePolad'
teaser: '../images/2024-frepolad.png'
authors: '<b>Chenliang Zhou</b>, Fangcheng Zhong, Param Hanji, Zhilin Guo, Kyle Fogarty, Alejandro Sztrajman, Hongyun Gao, Cengiz Oztireli'
---

We propose <em>FrePolad: <b>f</b>requency-<b>r</b>ectified <b>po</b>int <b>la</b>tent <b>d</b>diffusion</em>, a point cloud generation pipeline integrating a variational autoencoder (VAE) with a denoising diffusion probabilistic model (DDPM) for the latent distribution. FrePolad simultaneously achieves high quality, diversity, and flexibility in point cloud cardinality for generation tasks while maintaining high computational efficiency. The improvement in generation quality and diversity is achieved through (1) a novel frequency rectification via spherical harmonics designed to retain high-frequency content while learning the point cloud distribution; and (2) a latent DDPM to learn the regularized yet complex latent distribution. In addition, FrePolad supports variable point cloud cardinality by formulating the sampling of points as conditional distributions over a latent shape distribution. Finally, the low-dimensional latent space encoded by the VAE contributes to FrePolad's fast and scalable sampling. Our quantitative and qualitative results demonstrate FrePolad's state-of-the-art performance in terms of quality, diversity, and computational efficiency.

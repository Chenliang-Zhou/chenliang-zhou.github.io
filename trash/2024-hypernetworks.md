---
title: "Hypernetworks for Generalizable BRDF Representation"
collection: publications
permalink:
date: 2024-09-20
venue: 'ECCV'
link: 'https://faziletgokbudak.github.io/hyper-page/'
pdf: 'https://arxiv.org/pdf/2311.15783.pdf'
code: 'https://github.com/faziletgokbudak/Hyper-neural-materials'
teaser: '../images/2024-hypernetworks.png'
authors: 'Fazilet Gokbudak, Alejandro Sztrajman, <b>Chenliang Zhou</b>, Fangcheng Zhong, Rafal Mantiuk, Cengiz Oztireli'
---

In this paper, we introduce a technique to estimate measured BRDFs from a sparse set of samples. Our approach offers accurate BRDF reconstructions that are generalizable to new materials. This opens the door to BDRF reconstructions from a variety of data sources. The success of our approach relies on the ability of hypernetworks to generate a robust representation of BRDFs and a set encoder that allows us to feed inputs of different sizes to the architecture. The set encoder and the hypernetwork also enable the compression of densely sampled BRDFs. We evaluate our technique both qualitatively and quantitatively on the well-known MERL dataset of 100 isotropic materials. Our approach accurately 1) estimates the BRDFs of unseen materials even for an extremely sparse sampling, 2) compresses the measured BRDFs into very small embeddings, e.g., 7D.

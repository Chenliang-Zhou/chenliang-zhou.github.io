---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}

## MPhil/Part II Project Supervision

Part II and MPhil students are welcome to contact me to discuss their project ideas, especially related to 2D/3D generation/manipulation.

Some potential project ideas:

- [CLIP](https://openai.com/research/clip)-related
	- Theoretical exploration/analysis of CLIP space

	- Exploration of "object subspace": the subspace formed by different images/3D models of the same object

	- Use PAE in 3D or video editing/fine-tuning 

A thorough analysis/summary of the pros & cons of using/not using CLIP and using Diffusion/GAN.
Current good text2-3D models are text2NeRF, which is less useful for the artists who want to use it to generate a prototype model. Can we do text2mesh?
Most methods only support a one-off generation; Can we manipulate/fine-tune the 3D object (e.g., modifying details such as geometry, colour, lighting, or adding objects), probably guided by text? Or can we try this on image
Directly build CLIP3D (think about 3DMM etc. to encode 3D shapes?) (problem: data)
Doing something at the text end of CLIP?
Given to Zak: Improve CLIP (customized CLIP): retrain it using face data, or using a new distance (e.g. Mahalanobis), or change text encoder
Combine text-driven scene generation and object generation
Given to Jiale: Test the performance of CLIP/other language models when input is many sentences/paragraphs. Try paragraph to 2D/3D
(Text-driven) 3D vision tasks: detection/recognition/captioning/classification/segmentation: by projecting the object to 2D and using CLIP.
GET3D with only one view?



## MPhil/Part II Students

- Jiale Wang (MPhil; current): Paragraph2Image

- Zak Buzzard (Part II; current): Comparing CLIP Architectures

## Supervision and Teaching Assistant

### University of Cambridge

- [Artificial Intelligence](https://www.cl.cam.ac.uk/teaching/2223/ArtInt/), 2022-2023

- [Interaction Design](https://www.cl.cam.ac.uk/teaching/2223/IntDesign/), 2022-2023

- [Discrete Mathematics](https://www.cl.cam.ac.uk/teaching/2223/DiscMath/), 2022-2023

- [Logic and Proof](https://www.cl.cam.ac.uk/teaching/2223/LogicProof/), 2022-2023

- [Introduction to Graphics](https://www.cl.cam.ac.uk/teaching/2223/Graphics/), 2022-2023

### University of British Columbia

- CPSC 404: Advanced Relational Databases, 2019-2020

- CPSC 425: Computer Vision, 2019-2020

- CPSC 322: Introduction to Artificial Intelligence, 2018-2019

- CPSC 121: Models of Computation, 2017-2018


---
title: Learning Robotic Locomotion Affordances and Photorealistic Simulators from
  Human-Captured Data
abstract: 'Learning reliable affordance models which satisfy human preferences is
  often hindered by a lack of high-quality training data. Similarly, learning visuomotor
  policies in simulation can be challenging due to the high cost of photo-realistic
  rendering. We present PAWS: a comprehensive robot learning framework that uses a
  novel portable data capture rig and processing pipeline to collect long-horizon
  trajectories that include camera poses, foot poses, terrain meshes, and 3D radiance
  fields. We also contribute PAWS-Data: an extensive dataset gathered with PAWS containing
  over 10 hours of indoor and outdoor trajectories spanning a variety of scenes. With
  PAWS-Data we leverage radiance fields’ photo-realistic rendering to generate tens
  of thousands of viewpoint-augmented images, then produce pixel affordance labels
  by identifying semantically similar regions to those traversed by the user. On this
  data we finetune a navigation affordance model from a pretrained backbone, and perform
  detailed ablations. Additionally, We open source PAWS-Sim, a high-speed photo-realistic
  simulator which integrates PAWS-Data with IsaacSim, enabling research for visuomotor
  policy learning. We evaluate the utility of the affordance model on a quadrupedal
  robot, which plans through affordances to follow pathways and sidewalks, and avoid
  human collisions. Project resources are available on the [website](https://pawslocomotion.com).'
section: Poster
openreview: 1TEZ1hiY5m
video: https://youtu.be/JFOY4X6dw00?si=kbBrPU6m4i3jFbBB
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: escontrela25a
month: 0
tex_title: Learning Robotic Locomotion Affordances and Photorealistic Simulators from
  Human-Captured Data
firstpage: 5434
lastpage: 5445
page: 5434-5445
order: 5434
cycles: false
bibtex_author: Escontrela, Alejandro and Kerr, Justin and Stachowicz, Kyle and Abbeel,
  Pieter
author:
- given: Alejandro
  family: Escontrela
- given: Justin
  family: Kerr
- given: Kyle
  family: Stachowicz
- given: Pieter
  family: Abbeel
date: 2025-01-12
address:
container-title: Proceedings of The 8th Conference on Robot Learning
volume: '270'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 1
  - 12
pdf: https://raw.githubusercontent.com/mlresearch/v270/main/assets/escontrela25a/escontrela25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

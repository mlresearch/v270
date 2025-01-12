---
title: Large Scale Mapping of Indoor Magnetic Field by Local and Sparse Gaussian Processes
abstract: Magnetometer-based indoor navigation uses variations in the magnetic field
  to determine the robot’s location. For that, a magnetic map of the environment has
  to be built beforehand from a collection of localized magnetic measurements. Existing
  solutions built on sparse Gaussian Process (GP) regression do not scale well to
  large environments, being either slow or resulting in discontinuous prediction.
  In this paper, we propose to model the magnetic field of large environments based
  on GP regression. We first modify a deterministic training conditional sparse GP
  by accounting for magnetic field physics to map small environments efficiently.
  We then scale the model on larger scenes by introducing a local expert aggregation
  framework. It splits the scene into subdomains, fits a local expert on each, and
  then aggregates expert predictions in a differentiable and probabilistic way. We
  evaluate our model on real and simulated data and show that we can smoothly map
  a three-story building in a few hundred milliseconds.
section: Poster
openreview: edP2dmingV
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: abdul-raouf25a
month: 0
tex_title: Large Scale Mapping of Indoor Magnetic Field by Local and Sparse Gaussian
  Processes
firstpage: 2104
lastpage: 2119
page: 2104-2119
order: 2104
cycles: false
bibtex_author: ABDUL-RAOUF, Iad and Gay-Bellile, Vincent and JOLY, Cyril and Bourgeois,
  Steve and Paljic, Alexis
author:
- given: Iad
  family: ABDUL-RAOUF
- given: Vincent
  family: Gay-Bellile
- given: Cyril
  family: JOLY
- given: Steve
  family: Bourgeois
- given: Alexis
  family: Paljic
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
pdf: https://raw.githubusercontent.com/mlresearch/v270/main/assets/abdul-raouf25a/abdul-raouf25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

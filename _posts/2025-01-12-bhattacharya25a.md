---
title: Monocular Event-Based Vision for Obstacle Avoidance with a Quadrotor
abstract: We present the first static-obstacle avoidance method for quadrotors using
  just an onboard, monocular event camera. Quadrotors are capable of fast and agile
  flight in cluttered environments when piloted manually, but vision-based autonomous
  flight in unknown environments is difficult in part due to the sensor limitations
  of traditional onboard cameras. Event cameras, however, promise nearly zero motion
  blur and high dynamic range, but produce a very large volume of events under significant
  ego-motion and further lack a continuous-time sensor model in simulation, making
  direct sim-to-real transfer not possible. By leveraging depth prediction as a pretext
  task in our learning framework, we can pre-train a reactive obstacle avoidance events-to-control
  policy with approximated, simulated events and then fine-tune the perception component
  with limited events-and-depth real-world data to achieve obstacle avoidance in indoor
  and outdoor settings. We demonstrate this across two quadrotor-event camera platforms
  in multiple settings and find, contrary to traditional vision-based works, that
  low speeds (1m/s) make the task harder and more prone to collisions, while high
  speeds (5m/s) result in better event-based depth estimation and avoidance. We also
  find that success rates in outdoor scenes can be significantly higher than in certain
  indoor scenes.
section: Poster
openreview: 82bpTugrMt
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bhattacharya25a
month: 0
tex_title: Monocular Event-Based Vision for Obstacle Avoidance with a Quadrotor
firstpage: 4826
lastpage: 4843
page: 4826-4843
order: 4826
cycles: false
bibtex_author: Bhattacharya, Anish and Cannici, Marco and Rao, Nishanth and Tao, Yuezhan
  and Kumar, Vijay and Matni, Nikolai and Scaramuzza, Davide
author:
- given: Anish
  family: Bhattacharya
- given: Marco
  family: Cannici
- given: Nishanth
  family: Rao
- given: Yuezhan
  family: Tao
- given: Vijay
  family: Kumar
- given: Nikolai
  family: Matni
- given: Davide
  family: Scaramuzza
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
pdf: https://raw.githubusercontent.com/mlresearch/v270/main/assets/bhattacharya25a/bhattacharya25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---

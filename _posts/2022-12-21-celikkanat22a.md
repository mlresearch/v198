---
abstract: Networks have become indispensable and ubiquitous structures in many fields
  to model the interactions among different entities, such as friendship in social
  networks or protein interactions in biological graphs. A major challenge is to understand
  the structure and dynamics of these systems. Although networks evolve through time,
  most existing graph representation learning methods target only static networks.
  Whereas approaches have been developed for the modeling of dynamic networks, there
  is a lack of efficient continuous time dynamic graph representation learning methods
  that can provide accurate network characterization and visualization in low dimensions
  while explicitly accounting for prominent network characteristics such as homophily
  and transitivity. In this paper, we propose the Piecewise-Velocity Model (PiVeM)
  for the representation of continuous-time dynamic networks. It learns dynamic embeddings
  in which the temporal evolution of nodes is approximated by piecewise linear interpolations
  based on a latent distance model with piecewise constant node-specific velocities.
  The model allows for analytically tractable expressions of the associated Poisson
  process likelihood with scalable inference invariant to the number of events. We
  further impose a scalable Kronecker structured Gaussian Process prior to the dynamics
  accounting for community structure, temporal smoothness, and disentangled (uncorrelated)
  latent embedding dimensions optimally learned to characterize the network dynamics.
  We show that PiVeM can successfully represent network structure and dynamics in
  ultra-low two-dimensional embedding spaces. We further extensively evaluate the
  performance of the approach on various networks of different types and sizes and
  find that it outperforms existing relevant state-of-art methods in downstream tasks
  such as link prediction. In summary, PiVeM enables easily interpretable dynamic
  network visualizations and characterizations that can further improve our understanding
  of the intrinsic dynamics of time-evolving networks.
openreview: 48WaBYh_zbP
section: Poster Presentations
software: https://abdcelikkanat.github.io/projects/pivem/
title: Piecewise-Velocity Model for Learning Continuous-Time Dynamic Node Representations
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: celikkanat22a
month: 0
tex_title: Piecewise-Velocity Model for Learning Continuous-Time Dynamic Node Representations
firstpage: '36:1'
lastpage: '36:21'
page: 36:1-36:21
order: 36
cycles: false
bibtex_author: CELIKKANAT, Abdulkadir and Nakis, Nikolaos and M{\o}rup, Morten
author:
- given: Abdulkadir
  family: CELIKKANAT
- given: Nikolaos
  family: Nakis
- given: Morten
  family: Mørup
date: 2022-12-21
address:
container-title: Proceedings of the First Learning on Graphs Conference
volume: '198'
genre: inproceedings
issued:
  date-parts:
  - 2022
  - 12
  - 21
pdf: https://proceedings.mlr.press/v198/celikkanat22a/celikkanat22a.pdf
extras:
- label: Supplementary ZIP
  link: https://proceedings.mlr.press/v198/celikkanat22a/celikkanat22a-supp.zip
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

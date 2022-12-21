---
abstract: 'Graph Neural Networks (GNNs) have been shown to achieve competitive results
  to tackle graph-related tasks, such as node and graph classification, link prediction
  and node and graph clustering in a variety of domains. Most GNNs use a message passing
  framework and hence are called MPNNs. Despite their promising results, MPNNs have
  been reported to suffer from over-smoothing, over-squashing and under-reaching.
  Graph rewiring and graph pooling have been proposed in the literature as solutions
  to address these limitations. However, most state-of-the-art graph rewiring methods
  fail to preserve the global topology of the graph, are neither differentiable nor
  inductive, and require the tuning of hyper-parameters. In this paper, we propose
  DiffWire, a novel framework for graph rewiring in MPNNs that is principled, fully
  differentiable and parameter-free by leveraging the Lov{á}sz bound. The proposed
  approach provides a unified theory for graph rewiring by proposing two new, complementary
  layers in MPNNs: CT-Layer, a layer that learns the commute times and uses them as
  a relevance function for edge re-weighting; and GAP-Layer, a layer to optimize the
  spectral gap, depending on the nature of the network and the task at hand. We empirically
  validate the value of each of these layers separately with benchmark datasets for
  graph classification. We also perform preliminary studies on the use of CT-Layer
  for homophilic and heterophilic node classification tasks. DiffWire brings together
  the learnability of commute times to related definitions of curvature, opening the
  door to creating more expressive MPNNs. '
openreview: IXvfIex0mX6f
section: Poster Presentations
software: https://github.com/AdrianArnaiz/DiffWire
title: 'DiffWire: Inductive Graph Rewiring via the Lovász Bound'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: arnaiz-rodri-guez22a
month: 0
tex_title: 'DiffWire: Inductive Graph Rewiring via the Lov{á}sz Bound'
firstpage: '15:1'
lastpage: '15:27'
page: 15:1-15:27
order: 15
cycles: false
bibtex_author: Arnaiz-Rodr{\'\i}guez, Adri{\'a}n and Begga, Ahmed and Escolano, Francisco
  and Oliver, Nuria M
author:
- given: Adrián
  family: Arnaiz-Rodrı́guez
- given: Ahmed
  family: Begga
- given: Francisco
  family: Escolano
- given: Nuria M
  family: Oliver
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
pdf: https://proceedings.mlr.press/v198/arnaiz-rodri-guez22a/arnaiz-rodri-guez22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

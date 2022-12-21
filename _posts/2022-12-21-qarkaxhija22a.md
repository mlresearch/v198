---
abstract: We introduce De Bruijn Graph Neural Networks (DBGNNs), a novel time-aware
  graph neural network architecture for time-resolved data on dynamic graphs. Our
  approach accounts for temporal-topological patterns that unfold in the causal topology
  of dynamic graphs, which is determined by \emph{causal walks}, i.e. temporally ordered
  sequences of links by which nodes can influence each other over time. Our architecture
  builds on multiple layers of higher-order De Bruijn graphs, an iterative line graph
  construction where nodes in a De Bruijn graph of order \textdollar k\textdollar  represent
  walks of length \textdollar k-1\textdollar , while edges represent walks of length
  \textdollar k\textdollar . We develop a graph neural network architecture that utilizes
  De Bruijn graphs to implement a message passing scheme that considers non-Markovian
  characteristics of causal walks, which enables us to learn patterns in the causal
  topology of dynamic graphs. Addressing the issue that De Bruijn graphs with different
  orders \textdollar k\textdollar  can be used to model the same data, we apply statistical
  model selection to determine the optimal graph to be used for message passing. An
  evaluation in synthetic and empirical data sets suggests that DBGNNs can leverage
  temporal patterns in dynamic graphs, which substantially improves performance in
  a node classification task.
openreview: Dbkqs1EhTr
section: Poster Presentations
software: https://github.com/lisiq/dbgnn
title: 'De Bruijn Goes Neural: Causality-Aware Graph Neural Networks for Time Series
  Data on Dynamic Graphs'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: qarkaxhija22a
month: 0
tex_title: 'De Bruijn Goes Neural: Causality-Aware Graph Neural Networks for Time
  Series Data on Dynamic Graphs'
firstpage: '51:1'
lastpage: '51:21'
page: 51:1-51:21
order: 51
cycles: false
bibtex_author: Qarkaxhija, Lisi and Perri, Vincenzo and Scholtes, Ingo
author:
- given: Lisi
  family: Qarkaxhija
- given: Vincenzo
  family: Perri
- given: Ingo
  family: Scholtes
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
pdf: https://proceedings.mlr.press/v198/qarkaxhija22a/qarkaxhija22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

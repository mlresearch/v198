---
abstract: With the increasing use of Graph Neural Networks (GNNs) in critical real-world
  applications, several post hoc explanation methods have been proposed to understand
  their predictions. However, there has been no work in generating explanations on
  the fly during model training and utilizing them to improve the expressive power
  of the underlying GNN models. In this work, we introduce a novel explanation-directed
  neural message passing framework for GNNs, EXPASS (EXplainable message PASSing),
  which aggregates only embeddings from nodes and edges identified as important by
  a GNN explanation method. EXPASS can be used with any existing GNN architecture
  and subgraph-optimizing explainer to learn accurate graph embeddings. We theoretically
  show that EXPASS alleviates the oversmoothing problem in GNNs by slowing the layer-wise
  loss of Dirichlet energy and that the embedding difference between the vanilla message
  passing and EXPASS framework can be upper bounded by the difference of their respective
  model weights. Our empirical results show that graph embeddings learned using EXPASS
  improve the predictive performance and alleviate the oversmoothing problems of GNNs,
  opening up new frontiers in graph machine learning to develop explanation-based
  training frameworks.
openreview: _nlbNbawXDi
section: Poster Presentations
title: Towards Training GNNs Using Explanation Directed Message Passing
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: giunchiglia22a
month: 0
tex_title: Towards Training GNNs Using Explanation Directed Message Passing
firstpage: '28:1'
lastpage: '28:18'
page: 28:1-28:18
order: 28
cycles: false
bibtex_author: Giunchiglia, Valentina and Shukla, Chirag Varun and Gonzalez, Guadalupe
  and Agarwal, Chirag
author:
- given: Valentina
  family: Giunchiglia
- given: Chirag Varun
  family: Shukla
- given: Guadalupe
  family: Gonzalez
- given: Chirag
  family: Agarwal
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
pdf: https://proceedings.mlr.press/v198/giunchiglia22a/giunchiglia22a.pdf
extras: []
# Format based on citeproc: http://blog.martinfenner.org/2013/07/30/citeproc-yaml-for-bibliographies/
---

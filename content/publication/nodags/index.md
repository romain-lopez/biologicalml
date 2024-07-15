---
title: 'NODAGS-Flow: Nonlinear cyclic causal structure learning'
authors:
- Muralikrishnna G. Sethuraman
- Romain Lopez
- Rahul Mohan
- Faramarz Fekri
- Tommaso Biancalani
- Jan-Christian Hütter
date: '2023-04-01'
publishDate: '2024-07-14T02:46:26.627700Z'
publication_types:
- article-journal
publication: '*International Conference on Artificial Intelligence and Statistics*'
abstract: Learning causal relationships between variables is a well-studied problem
  in statistics, with many important applications in science. However, modeling real-world
  systems remain challenging, as most existing algorithms assume that the underlying
  causal graph is acyclic. While this is a convenient framework for developing theoretical
  developments about causal reasoning and inference, the underlying modeling assumption
  is likely to be violated in real systems, because feedback loops are common (e.g.,
  in biological systems). Although a few methods search for cyclic causal models,
  they usually rely on some form of linearity, which is also limiting, or lack a clear
  underlying probabilistic model. In this work, we propose a novel framework for learning
  nonlinear cyclic causal graphical models from interventional data, called NODAGS-Flow.
  We perform inference via direct likelihood optimization, employing techniques from
  residual normalizing flows for likelihood estimation. Through synthetic experiments
  and an application to single-cell high-content perturbation screening data, we show
  significant performance improvements with our approach compared to state-of-the-art
  methods with respect to structure recovery and predictive performance.
tags:
- conference
url_pdf: https://proceedings.mlr.press/v206/sethuraman23a
---

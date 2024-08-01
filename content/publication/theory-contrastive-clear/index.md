---
title: Toward the Identifiability of Comparative Deep Generative Models
authors:
- Romain Lopez
- Jan-Christian Huetter
- Ehsan Hajiramezanali
- Jonathan Pritchard
- Aviv Regev
date: '2024-04-01'
publishDate: '2024-08-01T06:18:30.290195Z'
publication_types:
- article-journal
publication: '*Causal Learning and Reasoning*'
abstract: Deep Generative Models (DGMs) are versatile tools for learning data representations
  while adequately incorporating domain knowledge such as the specification of conditional
  probability distributions. Recently proposed DGMs tackle the important task of comparing
  data sets from different sources. One such example is the setting of contrastive
  analysis that focuses on describing patterns that are enriched in a target data
  set compared to a background data set. The practical deployment of those models
  often assumes that DGMs naturally infer interpretable and modular latent representations,
  which is known to be an issue in practice. Consequently, existing methods often
  rely on ad-hoc regularization schemes, although without any theoretical grounding.
  Here, we propose a theory of identifiability for comparative DGMs by extending recent
  advances in the field of non-linear independent component analysis. We show that,
  while these models lack identifiability across a general class of mixing functions,
  they surprisingly become identifiable when the mixing function is piece-wise affine
  (e.g., parameterized by a ReLU neural network). We also investigate the impact of
  model misspecification, and empirically show that previously proposed regularization
  techniques for fitting comparative DGMs help with identifiability when the number
  of latent variables is not known in advance. Finally, we introduce a novel methodology
  for fitting comparative DGMs that improves the treatment of multiple data sources
  via multi-objective optimization and that helps adjust the hyperparameter for the
  regularization in an interpretable manner, using constrained optimization. We empirically
  validate our theory and new methodology using simulated data as well as a recent
  data set of genetic perturbations in cells profiled via single-cell RNA sequencing.
tags:
- conference
- featured
url_pdf: https://arxiv.org/abs/2401.15903
---

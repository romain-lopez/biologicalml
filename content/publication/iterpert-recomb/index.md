---
title: Sequential optimal experimental design of perturbation screens guided by multi-modal
  priors
authors:
- Kexin Huang
- Romain Lopez
- Jan-Christian Hütter
- Takamasa Kudo
- Antonio Rios
- Aviv Regev
date: '2024-01-01'
publishDate: '2024-08-01T06:18:30.302218Z'
publication_types:
- article-journal
publication: '*Research in Computational Molecular Biology (RECOMB)*'
abstract: Understanding a celltextquoterights expression response to genetic perturbations
  helps to address important challenges in biology and medicine, including the function
  of gene circuits, discovery of therapeutic targets and cell reprogramming and engineering.
  In recent years, Perturb-seq, pooled genetic screens with single cell RNA-seq (scRNA-seq)
  readouts, has emerged as a common method to collect such data. However, irrespective
  of technological advances, because combinations of gene perturbations can have unpredictable,
  non-additive effects, the number of experimental configurations far exceeds experimental
  capacity, and for certain cases, the number of available cells. While recent machine
  learning models, trained on existing Perturb-seq data sets, can predict perturbation
  outcomes with some degree of accuracy, they are currently limited by sub-optimal
  training set selection and the small number of cell contexts of training data, leading
  to poor predictions for unexplored parts of perturbation space. As biologists deploy
  Perturb-seq across diverse biological systems, there is an enormous need for algorithms
  to guide iterative experiments while exploring the large space of possible perturbations
  and their combinations. Here, we propose a sequential approach for designing Perturb-seq
  experiments that uses the model to strategically select the most informative perturbations
  at each step for subsequent experiments. This enables a significantly more efficient
  exploration of the perturbation space, while predicting the effect of the rest of
  the unseen perturbations with high-fidelity. Analysis of a previous large-scale
  Perturb-seq experiment reveals that our setting is severely restricted by the number
  of examples and rounds, falling into a non-conventional active learning regime called
  “active learning on a budget”. Motivated by this insight, we develop IterPert, a
  novel active learning method that exploits rich and multi-modal prior knowledge
  in order to efficiently guide the selection of subsequent perturbations. Using prior
  knowledge for this task is novel, and crucial for successful active learning on
  a budget. We validate IterPert using insilico benchmarking of active learning, constructed
  from a large-scale CRISPRi Perturb-seq data set. We find that IterPert outperforms
  other active learning strategies by reaching comparable accuracy at only a third
  of the number of perturbations profiled as the next best method. Overall, our results
  demonstrate the potential of sequentially designing perturbation screens through
  IterPert.
tags:
- conference
url_pdf: https://www.biorxiv.org/content/early/2023/12/13/2023.12.12.571389
---

---
title: Disentangling shared and group-specific variations in single-cell transcriptomics
  data with multiGroupVI
authors:
- Ethan Weinberger
- Romain Lopez
- Jan-Christian Hütter
- Aviv Regev
date: '2022-12-01'
publishDate: '2024-08-01T06:18:30.325078Z'
publication_types:
- article-journal
publication: '*Machine Learning in Computational Biology (MLCB)*'
abstract: Single-cell RNA sequencing (scRNA-seq) technologies have enabled a greater
  understanding of previously unexplored biological diversity. Based on the design
  of such experiments, individual cells from scRNA-seq datasets can often be attributed
  to non-overlapping “groups”. For example, these group labels may denote the cell’s
  tissue or cell line of origin. In this setting, one important problem consists in
  discerning patterns in the data that are shared across groups versus those that
  are group- specific. However, existing methods for this type of analysis are mainly
  limited to (generalized) linear latent variable models. Here we introduce multiGroupVI,
  a deep generative model for analyzing grouped scRNA-seq datasets that decomposes
  the data into shared and group-specific factors of variation. We first validate
  our approach on a simulated dataset, on which we significantly outperform state-of-the-art
  methods. We then apply it to explore regional differences in an scRNA-seq dataset
  sampled from multiple regions of the mouse small intestine.
tags:
- workshop
url_pdf: https://proceedings.mlr.press/v200/weinberger22a.html
url_code: https://github.com/Genentech/multiGroupVI
---

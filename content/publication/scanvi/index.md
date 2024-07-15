---
title: Probabilistic harmonization and annotation of single-cell transcriptomics data
  with deep generative models
authors:
- Chenling Xu*
- Romain Lopez*
- Edouard Mehlman*
- Jeffrey Regier
- Michael I. Jordan
- Nir Yosef
date: '2021-01-01'
publishDate: '2024-07-14T02:46:26.665454Z'
publication_types:
- article-journal
publication: '*Molecular Systems Biology*'
abstract: As single-cell transcriptomics becomes a mainstream technology, the natural
  next step is to integrate the accumulating data in order to achieve a common ontology
  of cell types and states. However, owing to various nuisance factors of variation,
  it is not straightforward how to compare gene expression levels across data sets
  and how to automatically assign cell type labels in a new data set based on existing
  annotations. In this manuscript, we demonstrate that our previously developed method,
  scVI, provides an effective and fully probabilistic approach for joint representation
  and analysis of cohorts of single-cell RNA-seq data sets, while accounting for uncertainty
  caused by biological and measurement noise. We also introduce single-cell ANnotation
  using Variational Inference (scANVI), a semi-supervised variant of scVI designed
  to leverage any available cell state annotations --- for instance when only one
  data set in a cohort is annotated, or when only a few cells in a single data set
  can be labeled using marker genes. We demonstrate that scVI and scANVI compare favorably
  to the existing methods for data integration and cell state annotation in terms
  of accuracy, scalability, and adaptability to challenging settings such as a hierarchical
  structure of cell state labels. We further show that different from existing methods,
  scVI and scANVI represent the integrated datasets with a single generative model
  that can be directly used for any probabilistic decision making task, using differential
  expression as our case study. scVI and scANVI are available as open source software
  and can be readily used to facilitate cell state annotation and help ensure consistency
  and reproducibility across studies.
tags:
- journal
url_pdf: https://www.embopress.org/doi/full/10.15252/msb.20209620
url_code: https://github.com/YosefLab/scVI
---

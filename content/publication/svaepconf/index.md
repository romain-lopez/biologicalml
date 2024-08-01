---
title: Learning causal representations of single cells via sparse mechanism shift
  modeling
authors:
- Romain Lopez*
- Natasa Tagasovska*
- Stephen Ra
- Kyunghyun Cho
- Jonathan K. Pritchard
- Aviv Regev
date: '2023-04-01'
publishDate: '2024-08-01T06:18:30.321242Z'
publication_types:
- article-journal
publication: '*Conference on Causal Learning and Reasoning*'
abstract: Latent variable models have become a go-to tool for analyzing biological
  data, especially in the field of single-cell genomics. One remaining challenge is
  the identification of individual latent variables related to biological pathways,
  more generally conceptualized as disentanglement. Although versions of variational
  autoencoders that explicitly promote disentanglement were introduced and applied
  to single-cell genomics data, the theoretical feasibility of disentanglement from
  independent and identically distributed measurements has been challenged. Recent
  methods propose instead to leverage non-stationary data, as well as the sparse mechanism
  assumption in order to learn disentangled representations, with a causal semantic.
  Here, we explore the application of these methodological advances in the analysis
  of single-cell genomics data with genetic or chemical perturbations. We benchmark
  these methods on simulated single cell expression data to evaluate their performance
  regarding disentanglement, causal target identification and out-of-domain generalisation.
  Finally, by applying the approaches to a large-scale gene perturbation data set,
  we find that the model relying on the sparse mechanism shift hypothesis surpasses
  contemporary methods on a transfer learning task.
tags:
- conference
url_pdf: https://proceedings.mlr.press/v213/lopez23a
url_code: https://github.com/Genentech/sVAE
---

---
title: Decision-making with auto-encoding variational Bayes
authors:
- Romain Lopez
- Pierre Boyeau
- Nir Yosef
- Michael I. Jordan
- Jeffrey Regier
date: '2020-11-01'
publishDate: '2024-08-01T06:18:30.364689Z'
publication_types:
- article-journal
publication: '*Advances in Neural Information Processing Systems*'
abstract: To make decisions based on a model fit by auto-encoding variational Bayes
  (AEVB), practitioners often let the variational distribution serve as a surrogate
  for the posterior distribution. This approach yields biased estimates of the expected
  risk, and therefore poor decisions for two reasons. First, the model fit by AEVB
  may yield biased statistics relative to the underlying data distribution. Second,
  there may be strong discrepancies between the variational distribution and the posterior.  We
  explore how fitting the variational distribution based on several objective functions
  other than the ELBO, while continuing to fit the generative model based on the ELBO,
  affects the quality of downstream decisions. For a particular model that is amenable
  to analysis, we investigate how importance sampling error as well as the biases
  in model parameter estimates vary across several approximate posteriors when used
  as proposal distributions. Our theoretical results suggest that a posterior approximation
  distinct from the variational distribution should be used for making decisions.
  Motivated by these theoretical results, we propose learning several approximate
  proposals for the best model and combining them using multiple importance sampling
  for decision-making. In addition to toy examples, we present a full-fledged case
  study of single-cell RNA sequencing. In this challenging instance of multiple hypothesis
  testing, our proposed approach surpasses the current state of the art.
tags:
- conference
- featured
url_pdf: 
  https://papers.nips.cc/paper/2020/hash/357a6fdf7642bf815a88822c447d9dc4-Abstract.html
url_code: https://github.com/PierreBoyeau/decision-making-vaes
---

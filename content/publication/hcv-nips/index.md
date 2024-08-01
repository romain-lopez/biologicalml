---
title: Information constraints on auto-encoding variational Bayes
authors:
- Romain Lopez
- Jeffrey Regier
- Michael I. Jordan
- Nir Yosef
date: '2018-11-01'
publishDate: '2024-08-01T06:18:30.393329Z'
publication_types:
- article-journal
publication: '*Advances in Neural Information Processing Systems*'
abstract: Parameterizing the approximate posterior of a generative model with neural
  networks has become a common theme in recent machine learning research. While providing
  appealing flexibility, this approach makes it difficult to impose or assess structural
  constraints such as conditional independence. We propose a framework for learning
  representations that relies on Auto-Encoding Variational Bayes and whose search
  space is constrained via kernel-based measures of independence. In particular, our
  method employs the d-variable Hilbert-Schmidt Independence Criterion (dHSIC) to
  enforce independence between the latent representations and arbitrary nuisance factors.
  We show how to apply this method to a range of problems, including the problems
  of learning invariant representations and the learning of interpretable representations.
  We also present a full-fledged application to single-cell RNA sequencing (scRNA-seq).
  In this setting the biological signal is mixed in complex ways with sequencing errors
  and sampling effects. We show that our method out-performs the state-of-the-art
  in this domain.
tags:
- conference
- featured
url_pdf: 
  https://papers.nips.cc/paper/7850-information-constraints-on-auto-encoding-variational-bayes.pdf
url_code: https://github.com/romain-lopez/HCV
---

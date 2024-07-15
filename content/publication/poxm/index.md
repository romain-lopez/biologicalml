---
title: Learning from eXtreme bandit feedback
authors:
- Romain Lopez
- Inderjit Dhillon
- Michael I. Jordan
date: '2021-02-01'
publishDate: '2024-07-14T02:46:26.658229Z'
publication_types:
- article-journal
publication: '*AAAI Conference on Artificial Intelligence*'
abstract: We study the problem of batch learning from bandit feedback in the setting
  of extremely large action spaces. Learning from extreme bandit feedback is ubiquitous
  in recommendation systems, in which billions of decisions are made over millions
  of choices in a single day, yielding massive observational data. In these large-scale
  real-world applications, supervised learning approaches such as eXtreme Multi-label
  Classification (XMC) remain the standard approach despite the bias inherent in the
  data collection process. Conversely, previously developed importance sampling approaches
  are unbiased but suffer from impractical variance when dealing with a large number
  of actions.  In this paper, we introduce a selective importance sampling estimator
  (sIS) with more favorable bias-variance tradeoff. Specifically, sIS is obtained
  by performing importance sampling on the conditional expectation of the reward with
  respect to a small subset of actions for each instance (a form of Rao-Blackwellization).
  We employ this estimator in a novel algorithmic procedure---named Policy Optimization
  for eXtreme Models (POXM)---for learning from bandit feedback on XMC tasks. In POXM,
  the selected actions for the sIS estimator are the top-p actions of the logging
  policy, where p is adjusted from the data and is significantly smaller than the
  size of the action space.  We use a supervised-to-bandit conversion on three XMC
  datasets to benchmark our POXM method against BanditNet, a previously applied partial
  matching pruning strategy as well as a supervised learning baseline. Whereas BanditNet
  sometimes improves marginally over the logging policy, our experiments show that
  POXM systematically and significantly improves over all baselines.
tags:
- conference
url_pdf: https://ojs.aaai.org/index.php/AAAI/article/view/17058
---

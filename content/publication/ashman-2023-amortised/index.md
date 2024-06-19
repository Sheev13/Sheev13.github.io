---
title: Amortised Inference in Neural Networks for Small-Scale Probabilistic Meta-Learning
authors:
- Matthew Ashman
- Tommy Rochussen
- Adrian Weller
date: '2023-06-20'
publication_types: 'Workshop paper'
publication: '*Fifth Symposium on Advances in Approximate Bayesian Inference*'
links:
- name: URL
  url: https://arxiv.org/abs/2310.15786
abstract: The global inducing point variational approximation for BNNs is based on using a set of inducing inputs to construct a series of conditional distributions that accurately approximate the conditionals of the true posterior distribution. Our key insight is that these inducing inputs can be replaced by the actual data, such that the variational distribution consists of a set of approximate likelihoods for each datapoint. This structure lends itself to amortised inference, in which the parameters of each approximate likelihood are obtained by passing each datapoint through a meta-model known as the inference network. By training this inference network across related datasets, we can meta-learn Bayesian inference over task-specific BNNs.
---

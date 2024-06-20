---
title: "Amortised Inference in Bayesian Neural Networks
authors:
- "Tommy Rochussen"
date: '2023-09-06'
publication_types:
- thesis
publication: '*Master's Thesis*'
links:
- name: URL
  url: https://arxiv.org/abs/2309.03018
abstract: >
  Meta-learning is a framework in which machine learning models train over a set of datasets in order to produce predictions on new datasets at test time. Probabilistic meta-learning has received an abundance of attention from the research community in recent years, but a problem shared by many existing probabilistic meta-models is that they require a very large number of datasets in order to produce high-quality predictions with well-calibrated uncertainty estimates. In many applications, however, such quantities of data are simply not available. In this dissertation we present a significantly more data-efficient approach to probabilistic meta-learning through per-datapoint amortisation of inference in Bayesian neural networks, introducing the Amortised Pseudo-Observation Variational Inference Bayesian Neural Network (APOVI-BNN). First, we show that the approximate posteriors obtained under our amortised scheme are of similar or better quality to those obtained through traditional variational inference, despite the fact that the amortised inference is performed in a single forward pass. We then discuss how the APOVI-BNN may be viewed as a new member of the neural process family, motivating the use of neural process training objectives for potentially better predictive performance on complex problems as a result. Finally, we assess the predictive performance of the APOVI-BNN against other probabilistic meta-models in both a one-dimensional regression problem and in a significantly more complex image completion setting. In both cases, when the amount of training data is limited, our model is the best in its class.
---

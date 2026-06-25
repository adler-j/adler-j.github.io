---
title: "Learning to solve inverse problems using Wasserstein loss"
date: 2017-10-30
authors:
  - "Jonas Adler"
  - "Axel Ringh"
  - "Ozan Öktem"
  - "Johan Karlsson"
summary: "Compute the image-space Wasserstein loss using Sinkhorn iterations and use it for learning to solve inverse problems."
math: true
---

Jonas Adler, Axel Ringh, Ozan Öktem, Johan Karlsson  ·  *NIPS workshop in optimal transport*

We propose using the Wasserstein loss for training in inverse problems. In particular, we consider a learned primal-dual reconstruction scheme for ill-posed inverse problems using the Wasserstein distance as loss function in the learning. This is motivated by miss-alignments in training data, which when using standard mean squared error loss could severely degrade reconstruction quality. We prove that training with the Wasserstein loss gives a reconstruction operator that correctly compensates for miss-alignments in certain cases, whereas training with the mean squared error gives a smeared reconstruction. Moreover, we demonstrate these effects by training a reconstruction algorithm using both mean squared error and optimal transport loss for a problem in computerized tomography.

[PDF](https://arxiv.org/pdf/1710.10898)  ·  [Preprint](https://arxiv.org/abs/1710.10898)  ·  [Code](https://github.com/adler-j/wasserstein_inverse_problems)

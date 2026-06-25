---
title: "Accelerated Forward-Backward Optimization using Deep Learning"
date: 2021-05-12
authors:
  - "Sebastian Banert"
  - "Jevgenija Rudzusika"
  - "Ozan Öktem"
  - "Jonas Adler"
summary: "Provably convergent convex optimization using Deep Learning."
math: true
---

Sebastian Banert, Jevgenija Rudzusika, Ozan Öktem, Jonas Adler  ·  *arXiv*

We propose several deep-learning accelerated optimization solvers with convergence guarantees. We use ideas from the analysis of accelerated forward-backward schemes like FISTA, but instead of the classical approach of proving convergence for a choice of parameters, such as a step-size, we show convergence whenever the update is chosen in a specific set. Rather than picking a point in this set using some predefined method, we train a deep neural network to pick the best update. Finally, we show that the method is applicable to several cases of smooth and non-smooth optimization and show superior results to established accelerated solvers.

[PDF](https://arxiv.org/pdf/2105.05210.pdf)  ·  [Preprint](https://arxiv.org/abs/2105.05210)  ·  [Code](https://github.com/JevgenijaAksjonova/Deep-Optimization)

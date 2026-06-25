---
title: "Deep Bayesian Inversion"
date: 2018-11-16
authors:
  - "Jonas Adler"
  - "Ozan Öktem"
summary: "We use deep learning to perform bayesian inversion."
---

Jonas Adler, Ozan Öktem  ·  *arXiv*

Characterizing statistical properties of solutions of inverse problems is essential for decision making. Bayesian inversion offers a tractable framework for this purpose, but current approaches are computationally unfeasible for most realistic imaging applications in the clinic. We introduce two novel deep learning based methods for solving large-scale inverse problems using Bayesian inversion: a sampling based method using a WGAN with a novel mini-discriminator and a direct approach that trains a neural network using a novel loss function. The performance of both methods is demonstrated on image reconstruction in ultra low dose 3D helical CT. We compute the posterior mean and standard deviation of the 3D images followed by a hypothesis test to assess whether a 'dark spot' in the liver of a cancer stricken patient is present. Both methods are computationally efficient and our evaluation shows very promising performance that clearly supports the claim that Bayesian inversion is usable for 3D imaging in time critical applications.

[PDF](https://arxiv.org/pdf/1811.05910.pdf)  ·  [Preprint](https://arxiv.org/abs/1811.05910)

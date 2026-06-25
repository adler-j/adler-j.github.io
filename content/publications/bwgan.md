---
title: "Banach Wasserstein GAN"
date: 2018-06-18
authors:
  - "Jonas Adler"
  - "Sebastian Lunz"
summary: "Generalizing Wasserstein GAN with gradient penalty to Banach Spaces."
math: true
---

Jonas Adler, Sebastian Lunz  ·  *NIPS*

Wasserstein Generative Adversarial Networks (WGANs) can be used to generate realistic samples from complicated image distributions. The Wasserstein metric used in WGANs is based on a notion of distance between individual images, which induces a notion of distance between probability distributions of images. So far the community has considered ℓ2 as the underlying distance. We generalize the theory of WGAN with gradient penalty to Banach spaces, allowing practitioners to select the features to emphasize in the generator. We further discuss the effect of some particular choices of underlying norms, focusing on Sobolev norms. Finally, we demonstrate the impact of the choice of norm on model performance and show state-of-the-art inception scores for non-progressive growing GANs on CIFAR-10.

[PDF](https://arxiv.org/pdf/1806.06621)  ·  [Preprint](https://arxiv.org/abs/1806.06621)  ·  [Code](https://github.com/adler-j/bwgan)

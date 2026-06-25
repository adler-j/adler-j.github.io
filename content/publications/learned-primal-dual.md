---
title: "Learned Primal-Dual Reconstruction"
date: 2017-07-05
authors:
  - "Jonas Adler"
  - "Ozan Öktem"
summary: "By learning in both reconstruction and data domain, we can improve image reconstruction."
math: true
---

Jonas Adler, Ozan Öktem  ·  *IEEE - Transactions on Medical Imaging*

We propose the Learned Primal-Dual algorithm for tomographic reconstruction. The algorithm accounts for a (possibly non-linear) forward operator in a deep neural network by unrolling a proximal primal-dual optimization method, but where the proximal operators have been replaced with convolutional neural networks. The algorithm is trained end-to-end, working directly from raw measured data and it does not depend on any initial reconstruction such as FBP. <br><br>We compare performance of the proposed method on low dose CT reconstruction against FBP, TV, and deep learning based post-processing of FBP. For the Shepp-Logan phantom we obtain >6dB PSNR improvement against all compared methods. For human phantoms the corresponding improvement is 6.6dB over TV and 2.2dB over learned post-processing along with a substantial improvement in the SSIM. Finally, our algorithm involves only ten forward-back-projection computations, making the method feasible for time critical clinical applications.

[PDF](https://arxiv.org/pdf/1707.06474.pdf)  ·  [Preprint](https://arxiv.org/abs/1707.06474)  ·  [Code](https://github.com/adler-j/learned_primal_dual)

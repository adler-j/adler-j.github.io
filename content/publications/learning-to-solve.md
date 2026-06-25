---
title: "Solving ill-posed inverse problems using iterative deep neural networks"
date: 2017-04-13
authors:
  - "Jonas Adler"
  - "Ozan Öktem"
summary: "A deep learning scheme for solving inverse problems that incorporates knowledge about the data formation process, improving both speed and quality compared to classical methods."
math: true
---

Jonas Adler, Ozan Öktem  ·  *Inverse Problems*

We propose a partially learned approach for the solution of ill-posed inverse problems with not necessarily linear forward operators. The method builds on ideas from classical regularisation theory and recent advances in deep learning to perform learning while making use of prior information about the inverse problem encoded in the forward operator, noise model and a regularising functional. The method results in a gradient-like iterative scheme, where the 'gradient' component is learned using a convolutional network that includes the gradients of the data discrepancy and regulariser as input in each iteration.<br><br>We present results of such a partially learned gradient scheme on a non-linear tomographic inversion problem with simulated data from both the Sheep-Logan phantom as well as a head CT. The outcome is compared against filtered backprojection and total variation reconstruction and the proposed method provides a 5.4 dB PSNR improvement over the total variation reconstruction while being significantly faster, giving reconstructions of $512 \\times 512$  pixel images in about 0.4 s using a single graphics processing unit (GPU).

[PDF](https://arxiv.org/pdf/1704.04058)  ·  [Preprint](https://arxiv.org/abs/1704.04058)  ·  [Code](https://github.com/adler-j/learned_gradient_tomography)

---
title: "Task adapted reconstruction for inverse problems"
date: 2018-08-27
authors:
  - "Jonas Adler"
  - "Sebastian Lunz"
  - "Olivier Verdier"
  - "Carola-Bibiane Schönlieb"
  - "Ozan Öktem"
summary: "Task adapted reconstruction for inverse problems."
math: true
---

Jonas Adler, Sebastian Lunz, Olivier Verdier, Carola-Bibiane Schönlieb, Ozan Öktem  ·  *arXiv*

The paper considers the problem of performing a task defined on a model parameter that is only observed indirectly through noisy data in an ill-posed inverse problem. A key aspect is to formalize the steps of reconstruction and task as appropriate estimators (non-randomized decision rules) in statistical estimation problems. The implementation makes use of (deep) neural networks to provide a differentiable parametrization of the family of estimators for both steps. These networks are combined and jointly trained against suitable supervised training data in order to minimize a joint differentiable loss function, resulting in an end-to-end task adapted reconstruction method. The suggested framework is generic, yet adaptable, with a plug-and-play structure for adjusting both the inverse problem and the task at hand. More precisely, the data model (forward operator and statistical model of the noise) associated with the inverse problem is exchangeable, eg, by using neural network architecture given by a learned iterative method. Furthermore, any task that is encodable as a trainable neural network can be used. The approach is demonstrated on joint tomographic image reconstruction, classification and joint tomographic image reconstruction segmentation.

[PDF](https://arxiv.org/pdf/1809.00948)  ·  [Preprint](https://arxiv.org/abs/1809.00948)

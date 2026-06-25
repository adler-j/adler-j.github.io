---
title: "Model based learning for accelerated, limited-view 3D photoacoustic tomography"
date: 2017-08-31
authors:
  - "Andreas Hauptmann"
  - "Felix Lucka"
  - "Marta Betcke"
  - "Nam Huynh"
  - "Jonas Adler"
  - "Ben Cox"
  - "Paul Beard"
  - "Sebastien Ourselin"
  - "Simon Arridge"
summary: "Using gradient boosting we scale learned iterative reconstruction to a very large scale inverse problem."
math: true
---

Andreas Hauptmann, Felix Lucka, Marta Betcke, Nam Huynh, Jonas Adler, Ben Cox, Paul Beard, Sebastien Ourselin, Simon Arridge  ·  *IEEE - Transactions on Medical Imaging*

Recent advances in deep learning for tomographic reconstructions have shown great potential to create accurate and high quality images with a considerable speed-up. In this work we present a deep neural network that is specifically designed to provide high resolution 3D images from restricted photoacoustic measurements. The network is designed to represent an iterative scheme and incorporates gradient information of the data fit to compensate for limited view artefacts. Due to the high complexity of the photoacoustic forward operator, we separate training and computation of the gradient information. A suitable prior for the desired image structures is learned as part of the training. The resulting network is trained and tested on a set of segmented vessels from lung CT scans and then applied to in-vivo photoacoustic measurement data.

[PDF](https://arxiv.org/pdf/1708.09832)  ·  [Preprint](https://arxiv.org/abs/1708.09832)  ·  [Code](https://github.com/asHauptmann/3DPAT_DGD)

---
title: Monocular depth estimation using a multi-grid attention-based model
publication_types:
  - "2"
authors:
  - Sangam Man Buddhacharya
  - Rabin Adhikari
  - Nischal Maharjan
  - Sanjeeb Prasad Panday
doi: https://doi.org/10.36548/jiip.2022.3.001
publication: Journal of Innovative Image Processing
abstract: With the increased use of depth information in computer vision,
  monocular depth estimation has been an emerging ﬁeld of study. It is a
  challenging task where many deep convolutional neural network-based methods
  have been used for depth prediction. The problem with most of these approaches
  is that they use a repeated combination of max-pooling and striding in an
  encoder, which reduces spatial resolution. In addition, these approaches use
  information from all the channels directly from the encoder, which is prone to
  noise. Addressing these issues, we present a multigrid attention-based
  densenet-161 model. It consists of a multigrid densenet-161 encoder that
  increases the spatial resolution and an attention-based decoder to select the
  important information from low-level features. We achieved absolute relative
  error (Absrel) of 0.109 and 0.0724 on NYU v2 and KITTI, dataset respectively.
  Our proposed method exceeded most evaluation measures with fewer parameters
  compared to the state-of-the-art on standard benchmark datasets. We produce a
  dense depth map from a single RGB image which can be used to create a dense
  point cloud. The anticipated depth map is accurate and smooth, which can be
  used in several applications.
draft: false
featured: false
image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2022-08-12T12:27:57.796Z
---

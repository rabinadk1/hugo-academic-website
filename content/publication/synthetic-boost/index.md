---
title: "Synthetic Boost: Leveraging Synthetic Data for Enhanced Vision-Language Segmentation in Echocardiography"
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types:
  - "1"
authors:
  - admin
  - Manish Dhakal
  - Safal Thapaliya
  - Kanchan Poudel
  - Prasiddha Bhandari
  - Bishesh Khanal
author_notes:
  - "Equal contribution"
  - "Equal contribution"
  - "Equal contribution"
publication: International Workshop on Advances in Simplifying Medical Ultrasound (ASMUS), co-located with MICCAI
abstract: Accurate segmentation is essential for echocardiography-based assessment of cardiovascular diseases (CVDs). However, the variability among sonographers and the inherent challenges of ultrasound images hinder precise segmentation. By leveraging the joint representation of image and text modalities, Vision-Language Segmentation Models (VLSMs) can incorporate rich contextual information, potentially aiding in accurate and explainable segmentation. However, the lack of readily available data in echocardiography hampers the training of VLSMs. In this study, we explore using synthetic datasets from Semantic Diffusion Models (SDMs) to enhance VLSMs for echocardiography segmentation. We evaluate results for two popular VLSMs (CLIPSeg and CRIS) using seven different kinds of language prompts derived from several attributes, automatically extracted from echocardiography images, segmentation masks, and their metadata. Our results show improved metrics and faster convergence when pretraining VLSMs on SDM-generated synthetic images before finetuning on real images. The code, configs, and prompts are available at https://github.com/naamiinepal/synthetic-boost.
draft: false
featured: false

doi: 10.1007/978-3-031-44521-7_9
url_pdf: https://arxiv.org/pdf/2309.12829.pdf
url_code: https://github.com/naamiinepal/synthetic-boost
url_slides: /uploads/slides/synthetic-boost.pdf

image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-09-22T18:27:57.796Z
---

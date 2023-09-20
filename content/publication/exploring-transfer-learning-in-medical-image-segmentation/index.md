---
title: Exploring Transfer Learning in Medical Image Segmentation using Vision-Language Models
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types:
  - "3"
authors:
  - Kanchan Poudel
  - Manish Dhakal
  - Prasiddha Bhandari
  - admin
  - Safal Thapaliya
  - Bishesh Khanal
publication: arXiv preprint arXiv:2308.07706 
abstract: |2-
    Medical Image Segmentation is crucial in various clinical applications within the medical domain. While state-of-the-art segmentation models have proven effective, integrating textual guidance to enhance visual features for this task remains an area with limited progress. Existing segmentation models that utilize textual guidance are primarily trained on open-domain images, raising concerns about their direct applicability in the medical domain without manual intervention or fine-tuning.

    To address these challenges, we propose using multimodal vision-language models for capturing semantic information from image descriptions and images, enabling the segmentation of diverse medical images. This study comprehensively evaluates existing vision language models across multiple datasets to assess their transferability from the open domain to the medical field. Furthermore, we introduce variations of image descriptions for previously unseen images in the dataset, revealing notable variations in model performance based on the generated prompts.

    Our findings highlight the distribution shift between the open-domain images and the medical domain and show that the segmentation models trained on open-domain images are not directly transferrable to the medical field. But their performance can be increased by finetuning them in the medical datasets. We report the zero-shot and finetuned segmentation performance of 4 Vision Language Models (VLMs) on 11 medical datasets using 9 types of prompts derived from 14 attributes.
draft: false
featured: false

url_pdf: https://arxiv.org/pdf/2308.07706.pdf

image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-08-15T12:27:57.796Z
---

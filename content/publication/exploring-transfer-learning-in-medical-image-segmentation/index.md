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
author_notes:
  - "Equal contribution"
  - "Equal contribution"
  - "Equal contribution"
  - "Equal contribution"
  - "Equal contribution"
publication: arXiv preprint arXiv:2308.07706 
abstract: |2-
    Medical image segmentation with deep learning is an important and widely studied topic because segmentation enables quantifying target structure size and shape that can help in disease diagnosis, prognosis, surgery planning, and understanding. Recent advances in the foundation Vision-Language Models (VLMs) and their adaptation to segmentation tasks in natural images with Vision-Language Segmentation Models (VLSMs) have opened up a unique opportunity to build potentially powerful segmentation models for medical images that enable providing helpful information via language prompt as input, leverage the extensive range of other medical imaging datasets by pooled dataset training, adapt to new classes, and be robust against out-of-distribution data with human-in-the-loop prompting during inference. Although transfer learning from natural to medical images for image-only segmentation models has been studied, no studies have analyzed how the joint representation of vision-language transfers to medical images in segmentation problems and understand gaps in leveraging their full potential.

    We present the first benchmark study on transfer learning of VLSMs to 2D medical images with thoughtfully collected 11 existing 2D medical image datasets of diverse modalities with carefully presented 9 types of language prompts from 14 attributes. Our results indicate that VLSMs trained in natural image-text pairs transfer reasonably to the medical domain in zero-shot settings when prompted appropriately for non-radiology photographic modalities; when finetuned, they obtain comparable performance to conventional architectures, even in X-rays and ultrasound modalities. However, the additional benefit of language prompts during finetuning may be limited, with image features playing a more dominant role; they can better handle training on pooled datasets combining diverse modalities and are potentially more robust to domain shift than the conventional segmentation models.
draft: false
featured: true

url_pdf: https://arxiv.org/pdf/2308.07706.pdf
url_code: https://github.com/naamiinepal/medvlsm

image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2023-08-15T12:27:57.796Z
---

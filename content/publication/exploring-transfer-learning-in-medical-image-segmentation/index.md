---
title: Exploring Transfer Learning in Medical Image Segmentation using Vision-Language Models
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types:
  - 1
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
publication: Medical Imaging with Deep Learning (MIDL)
abstract: Medical image segmentation allows quantifying target structure size and shape, aiding in disease diagnosis, prognosis, surgery planning, and comprehension. Building upon recent advancements in foundation Vision-Language Models (VLMs) from natural image-text pairs, several studies have proposed adapting them to Vision-Language Segmentation Models (VLSMs) that allow using language text as an additional input to segmentation models. Introducing auxiliary information via text with human-in-the-loop prompting during inference opens up unique opportunities, such as open vocabulary segmentation and potentially more robust segmentation models against out-of-distribution data. Although transfer learning from natural to medical images has been explored for image-only segmentation models, the joint representation of vision-language in segmentation problems remains underexplored. This study introduces the first systematic study on transferring VLSMs to 2D medical images, using carefully curated 11 datasets encompassing diverse modalities and insightful language prompts and experiments. Our findings demonstrate that although VLSMs show competitive performance compared to image-only models for segmentation after finetuning in limited medical image datasets, not all VLSMs utilize the additional information from language prompts, with image features playing a dominant role. While VLSMs exhibit enhanced performance in handling pooled datasets with diverse modalities and show potential robustness to domain shifts compared to conventional segmentation models, our results suggest that novel approaches are required to enable VLSMs to leverage the various auxiliary information available through language prompts. The code and datasets are available at https://github.com/naamiinepal/medvlsm.
draft: false
featured: true

url_pdf: https://openreview.net/pdf?id=sN3sDKkGeN
url_code: https://github.com/naamiinepal/medvlsm
url_slides: /uploads/slides/exploring-transfer-learning-in-medical-image-segmentation.pdf

image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2024-06-06T12:27:57.796Z
---

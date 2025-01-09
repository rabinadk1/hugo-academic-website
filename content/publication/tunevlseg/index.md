---
title: "TuneVLSeg: Prompt Tuning Benchmark for Vision-Language Segmentation Models"
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types:
  - 1
authors:
  - admin
  - Safal Thapaliya
  - Manish Dhakal
  - Bishesh Khanal
publication: Proceedings of the Asian Conference on Computer Vision (ACCV)
abstract: Vision-Language Models (VLMs) have shown impressive performance in vision tasks, but adapting them to new domains often requires expensive fine-tuning. Prompt tuning techniques, including textual, visual, and multimodal prompting, offer efficient alternatives by leveraging learnable prompts. However, their application to Vision-Language Segmentation Models (VLSMs) and evaluation under significant domain shifts remain unexplored. This work presents an open-source benchmarking framework, TuneVLSeg, to integrate various unimodal and multimodal prompt tuning techniques into VLSMs, making prompt tuning usable for downstream segmentation datasets with any number of classes. TuneVLSeg includes 6 prompt tuning strategies on various prompt depths used in 2 VLSMs totaling of 8 different combinations. We test various prompt tuning on 8 diverse medical datasets, including 3 radiology datasets (breast tumor, echocardiograph, chest X-ray pathologies) and 5 non-radiology datasets (polyp, ulcer, skin cancer), and two natural domain segmentation datasets. Our study found that textual prompt tuning struggles under significant domain shifts, from natural-domain images to medical data. Furthermore, visual prompt tuning, with fewer hyperparameters than multimodal prompt tuning, often achieves performance competitive to multimodal approaches, making it a valuable first attempt. Our work advances the understanding and applicability of different prompt-tuning techniques for robust domain-specific segmentation. The source code is available at https://github.com/naamiinepal/tunevlseg.
draft: false
featured: true

url_pdf: https://openaccess.thecvf.com/content/ACCV2024/papers/Adhikari_TuneVLSeg_Prompt_Tuning_Benchmark_for_Vision-Language_Segmentation_Models_ACCV_2024_paper.pdf
url_code: https://github.com/naamiinepal/tunevlseg

image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2024-12-07T00:00:00.000Z
---

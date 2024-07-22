---
title: "VLSM-Adapter: Finetuning Vision-Language Segmentation Efficiently with Lightweight Blocks"
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types:
  - 3
authors:
  - Manish Dhakal
  - admin
  - Safal Thapaliya
  - Bishesh Khanal
publication: arXiv preprint arXiv:2405.06196
abstract: Foundation Vision-Language Models (VLMs) trained using large-scale open-domain images and text pairs have recently been adapted to develop Vision-Language Segmentation Models (VLSMs) that allow providing text prompts during inference to guide image segmentation. If robust and powerful VLSMs can be built for medical images, it could aid medical professionals in many clinical tasks where they must spend substantial time delineating the target structure of interest. VLSMs for medical images resort to fine-tuning base VLM or VLSM pretrained on open-domain natural image datasets due to fewer annotated medical image datasets; this fine-tuning is resource-consuming and expensive as it usually requires updating all or a significant fraction of the pretrained parameters. Recently, lightweight blocks called adapters have been proposed in VLMs that keep the pretrained model frozen and only train adapters during fine-tuning, substantially reducing the computing resources required. We introduce a novel adapter, VLSM-Adapter, that can fine-tune pretrained vision-language segmentation models using transformer encoders. Our experiments in widely used CLIP-based segmentation models show that with only 3 million trainable parameters, the VLSM-Adapter outperforms state-of-the-art and is comparable to the upper bound end-to-end fine-tuning. The source code is available at https://github.com/naamiinepal/vlsm-adapter.
draft: false
featured: false

url_pdf: https://arxiv.org/pdf/2405.06196
url_code: https://github.com/naamiinepal/vlsm-adapter

image:
  filename: ""
  focal_point: Smart
  preview_only: false
date: 2024-05-10T12:27:57.796Z
---

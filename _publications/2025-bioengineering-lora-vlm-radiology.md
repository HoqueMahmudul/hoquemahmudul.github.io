---
title: "An Empirical Evaluation of Low-Rank Adapted Vision–Language Models for Radiology Image Captioning"
collection: publications
permalink: /publication/2025-bioengineering-lora-vlm-radiology
excerpt: 'Systematic evaluation of ten multimodal models fine-tuned with LoRA on the ROCOv2 dataset for radiology image captioning, comparing large and small vision-language models on relevance and factuality metrics.'
date: 2025-12-04
venue: 'Bioengineering'
paperurl: 'https://doi.org/10.3390/bioengineering12121330'
---

**Authors:** Mahmudul Hoque, Raisa Nusrat Chowdhury, Md Rakibul Hasan, Ojonugwa Oluwafemi Ejiga Peter, Fahmi Khalifa, Md Mahmudur Rahman

**Publisher:** MDPI  
**Journal:** Bioengineering, 2025, 12(12), 1330  
**Publication Date:** December 4, 2025

---

## Abstract

Rapidly growing medical imaging volumes have increased radiologist workloads, creating demand for automated tools that support interpretation and reduce reporting delays. Vision-language models (VLMs) can generate clinically relevant captions to accelerate report drafting, yet their varying parameter scales require systematic evaluation for clinical utility. This study evaluated ten multimodal models fine-tuned on the Radiology Objects in Context version 2 (ROCOv2) dataset containing 116,635 images across eight modalities. We compared four Large VLMs (LVLMs) including LLaVA variants and IDEFICS-9B against four Small VLMs (SVLMs) including MoonDream2, Qwen variants, and SmolVLM, alongside two fully fine-tuned baseline architectures (VisionGPT2 and CNN-Transformer). Low-Rank Adaptation (LoRA), applied to fewer than 1% of selected model parameters, proved optimal among adaptation strategies, outperforming broader LoRA configurations. Models were assessed on relevance (semantic similarity) and factuality (concept-level correctness) metrics. Performance showed clear stratification: LVLMs (0.273 to 0.317 overall), SVLMs (0.188 to 0.279), and baselines (0.154 to 0.177). LLaVA-Mistral-7B achieved the highest performance with relevance and factuality scores of 0.516 and 0.118, respectively, substantially exceeding the VisionGPT2 baseline (0.325, 0.028). Among the SVLMs, MoonDream2 demonstrated competitive relevance (0.466), approaching the performance of some LVLMs despite its smaller size. To investigate performance enhancement strategies for underperforming SVLMs, we prepended predicted imaging modality labels at inference time, which yielded variable results. These findings provide quantitative benchmarks for VLM selection in medical imaging, demonstrating that while model scale influences performance, architectural design and targeted adaptation enable select compact models to achieve competitive results.

## Keywords

Vision-language models, medical image captioning, radiology report generation, Low-Rank Adaptation, ROCOv2 dataset, caption quality, parameter-efficient fine-tuning

---

[Paper Link](https://doi.org/10.3390/bioengineering12121330)

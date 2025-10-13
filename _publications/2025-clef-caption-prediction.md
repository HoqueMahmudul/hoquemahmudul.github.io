---
title: "Modality-Guided Radiology Caption Prediction with Small Vision-Language Models and Image Classifier"
collection: publications
permalink: /publication/2025-clef-caption-prediction
excerpt: 'Investigation of small vision-language models with modality classification for efficient radiology caption generation at ImageCLEFmedical 2025.'
date: 2025-09-01
venue: 'CLEF 2025, CEUR Workshop Proceedings'
paperurl: 'https://ceur-ws.org/Vol-4038/paper_187.pdf'
---

**Authors:** Raisa Nusrat Chowdhury, Mahmudul Hoque, Md Rakibul Hasan, Ejiga Peter Ojonugwa Oluwafemi, Md Mahmudur Rahman

**Publisher:** CEUR-WS.org  
**Location:** Madrid, Spain  
**Publication Date:** 2025

---

## Abstract

This working note describes our contributions to the ImageCLEFmedical 2025 Caption Prediction subtask, in which we investigated various approaches for extracting clinically relevant captions from radiological data. We made six unique submissions. Our study focused on modifying three vision-language models—Qwen-2B, Qwen2.5-3B, and SmolVLM-500M—using the ROCOv2 dataset, which contains radiological image-caption pairings. Three of our submissions employed direct caption generation, whereas the remaining three incorporated an additional image modality classification phase with a ResNet-50 model. The classifier output (e.g., CT, MRI, Ultrasound, Radiograph) was included into the prompt to enhance caption generating efficacy. Among all submissions, Qwen 2B (2B params) emerges as the strongest overall performer, achieving the best scores in Overall (0.2316), Similarity (0.5704), ROUGE (0.1598), Relevance (0.3717), UMLS Concepts F1 (0.0741), AlignScore (0.1087), and Factuality Average (0.0914). These results indicate that Qwen 2B is highly effective at producing clinically accurate and factually aligned captions. In contrast, SmolVLM (Classification) leads in BERTScore (0.5375) and BLEURT (0.2576), suggesting that it excels in capturing semantic meaning and producing fluent, human-like text. These complementary strengths reflect different modeling priorities: Qwen 2B focuses more on factual and structural alignment, while SmolVLM emphasizes linguistic similarity and coherence. These findings underscore the effectiveness of hybrid pipelines that combine classification with prompt adaptation. Moreover, they show that even resource-efficient models, when fine-tuned and guided properly, can provide clinically valuable outputs. Our experiments support the ongoing shift toward smaller, adaptable vision–language systems for medical AI, offering practical potential for deployment in low-resource settings.

## Keywords

Vision Language Model, Medical Image Captioning, Qwen2.5-VL, Qwen2-VL, SmolVLM

---

[Paper Link](https://ceur-ws.org/Vol-4038/paper_187.pdf)

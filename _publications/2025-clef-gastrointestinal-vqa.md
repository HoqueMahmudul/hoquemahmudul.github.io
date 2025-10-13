---
title: "Solving Medical Data Limitations Through AI: Multi-Modal Vision-Language Learning for Gastrointestinal VQA and Synthetic Training Data Generation"
collection: publications
permalink: /publication/2025-clef-gastrointestinal-vqa
excerpt: 'Dual-task framework integrating visual question answering and synthetic image generation for gastrointestinal diagnostics using parameter-efficient fine-tuning.'
date: 2025-09-01
venue: 'CLEF 2025, CEUR Workshop Proceedings'
paperurl: 'https://ceur-ws.org/Vol-4038/paper_199.pdf'
---

**Authors:** Ejiga Peter Ojonugwa Oluwafemi, Mahmudul Hoque, Ejiga Frederick Akor, Raisa Nusrat Chowdhury, A. Umar, Md Mahmudur Rahman

**Publisher:** CEUR-WS.org  
**Location:** Madrid, Spain  
**Publication Date:** 2025

---

## Abstract

Gastrointestinal image analysis is crucial for early disease detection but faces challenges including data scarcity, privacy concerns, and limited automated diagnostic support. Traditional medical visual question answering (VQA) systems struggle with domain-specific knowledge and insufficient training data, while existing synthetic image generation methods fail to maintain the clinical authenticity required for medical applications. This paper presents a dual-task multi-modal framework integrating VQA and synthetic image generation to address these limitations. The methodology employs parameter-efficient fine-tuning of Florence-2 on the Kvasir-VQA dataset (6,500 gastrointestinal images), freezing the DaViT vision encoder while fine-tuning language components with cross-attention fusion for Sub-task 1. For Sub-task 2, the approach implements LoRA-enhanced Stable Diffusion 2.1 with rank-8 adaptation, incorporating structured clinical prompts for medically relevant synthetic image generation. Evaluation using standard NLP metrics (BLEU, ROUGE, METEOR) for VQA and image quality metrics (FBD, Fidelity, Agreement, Diversity) demonstrates significant improvements over baseline methods. The VQA system achieves ROUGE-L of 0.91, ROUGE-1 of 0.92, BLEU of 0.24, and METEOR of 0.50, substantially outperforming existing approaches. Synthetic image generation attains an optimal FBD of 1449.63 with fidelity of 0.29 and agreement of 0.73 while maintaining clinical authenticity. The parameter-efficient approach reduces computational requirements by 60% compared to full fine-tuning while achieving superior performance. Comprehensive ablation studies validate design choices, demonstrating cross-attention fusion effectiveness and optimal rank-8 LoRA configuration, providing enhanced gastrointestinal diagnostic support and privacy-preserving data augmentation.

## Keywords

Medical VQA, ImageCLEFmed 2025, Multimodal AI, Clinical Question Answering, Synthetic GI Images, Florence-2, LoRA, Stable Diffusion, Parameter-Efficient Fine-tuning, PEFT, Gastrointestinal Diagnostics, Polyp Detection, Synthetic Medical Imaging, Vision Transformers, Medical Imaging

---

[Paper Link](https://ceur-ws.org/Vol-4038/paper_199.pdf)

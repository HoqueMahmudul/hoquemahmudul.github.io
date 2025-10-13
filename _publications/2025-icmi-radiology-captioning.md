---
title: "Comparative Analysis of Fine-Tuned Multimodal Models in Radiology Image Captioning"
collection: publications
permalink: /publication/2025-icmi-radiology-captioning
excerpt: 'Comparison of selectively fine-tuned multimodal models for automated radiology image captioning, demonstrating efficient LoRA-based adaptation.'
date: 2025-04-05
venue: '2025 IEEE 4th International Conference on Computing and Machine Intelligence (ICMI)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/11141312'
---

**Authors:** Mahmudul Hoque, Md Rakibul Hasan, Md Ismail Siddiqi Emon, Ejiga Peter Ojonugwa Oluwafemi, Md Mahmudur Rahman, Fahmi Khalifa

**Publisher:** IEEE  
**Pages:** 1-6  
**Publication Date:** April 5, 2025

---

## Abstract

Multimodal artificial intelligence (AI) models offer a promising approach for automatically generating captions from radiology images, bridging visual and textual data to enhance medical image interpretation. This study compares a selectively fine-tuned Large Multimodal Model (LMM) with a fully fine-tuned multimodal encoder-decoder architecture on a subset of the Radiology Objects in Context version 2 (ROCOv2) dataset. Specifically, Vision Generative Pretrained Transformer 2 (VisionGPT-2) is evaluated against Large Language and Vision Assistant (LLaVA) version 1.6, a Mistral-7B-based LMM adapted using Low-Rank Adaptation (LoRA) on selected projection matrices. 

Experimental results show that LLaVA-1.6 outperforms VisionGPT-2 while significantly reducing the computational cost of full fine-tuning through selective adaptation with LoRA. Performance gains are observed across multiple metrics, including MedBERTScore (0.633), ClinicalBLEURT (0.456), ROUGE (0.251), BLEU-1 (0.209), BLEURT (0.317), METEOR (0.092), CIDEr (0.245), CLIPScore (0.816), RefCLIPScore (0.815), and BERTScore (0.628). These findings underscore the potential of selectively fine-tuned LMMs for efficient, semantically rich caption generation in medical imaging tasks, particularly in contexts constrained by sensitive data and limited computational resources.

## Keywords

Large Multimodal Model, Transformer, Large Language and Vision Assistant, Mistral-7B, Medical Image Analysis, Low-Rank Adaptation, Multimodal Data, Radiology Image Captioning, Vision Generative Pre-Trained Transformer-2

---

[Paper Link](https://ieeexplore.ieee.org/abstract/document/11141312)

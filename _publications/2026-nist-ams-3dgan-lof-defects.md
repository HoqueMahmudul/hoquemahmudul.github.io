---
title: "Generative modeling of additive manufacturing lack-of-fusion defects using three-dimensional adversarial network"
collection: publications
permalink: /publication/2026-nist-ams-3dgan-lof-defects
excerpt: 'A 3D-GAN framework for generating synthetic lack-of-fusion pore structures from XCT scans of additively manufactured CoCr parts, with applications in NDE and digital twin development.'
date: 2026-01-23
venue: 'Advanced Manufacturing Series (NIST AMS)'
paperurl: 'https://doi.org/10.6028/NIST.AMS.100-73'
---

**Authors:** Mahmudul Hoque, Felix Kim

**Publisher:** National Institute of Standards and Technology (NIST)  
**Report Number:** NIST AMS 100-73  
**Publication Date:** January 23, 2026

---

## Abstract

This paper presents a three-dimensional generative adversarial network (3D-GAN) framework to generate synthetic pore structures representative of lack-of-fusion (LOF) defects found in additively manufactured (AM) parts. The framework is trained on pores segmented from X-ray computed tomography (XCT) scans of four cobalt chromium (CoCr) disk samples produced by varying laser powder bed fusion (LPBF) process parameters (scan speed and hatch spacing). Synthetic pores of varying sizes and shapes are generated. A component aware loss module is incorporated into the adversarial learning process of the 3D-GAN to reduce fragmentation of generated pore structures. This method led to improved structural coherence relative to post-processing morphological closing operations. The synthetic pores' principal axis length ratio (PAR) and shape parameter (SP) are measured for morphometric analysis. Their distributions approximate the statistical trends observed in the training pore population. A registration approach was applied at the pore level to compare the similarity between synthetic pores. This ensured accurate calculation of intersection over union (IoU) to quantify shape similarity and structural uniqueness. Observed IoU values reflect low overlap between the different synthetic pores, suggesting the model synthesizes structurally distinct pores while maintaining the morphological realism of LOF defects. An additional experiment demonstrated the model's capacity to interpolate between known pore volumes and moderately extrapolate beyond the training distribution. A pore seeding framework is implemented to illustrate an application of synthetic pores in XCT simulation. Synthetic pores of specified sizes and quantities are embedded into an example AM part design, generating ground truth (GT) images with controlled defect populations. The study generated 3 503 synthetic and training pores. The framework can be adapted to generate synthetic data sets for other types of AM defects. Consequently, this work lays a foundation for advancing non-destructive evaluation (NDE) techniques, improving defect detection, and enabling development of digital twin frameworks for AM applications.

## Keywords

Additive manufacturing, defect, pore generation, three-dimensional generative adversarial network, defect dataset development, pore morphology, component aware loss module, volumetric image registration, XCT simulation, non-destructive evaluation

---

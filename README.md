# 🔄 Test-Time Adaptation for Robust Computer Vision

This repository presents my research and explorations around **Test-Time Adaptation (TTA)** techniques in computer vision. 
The goal is to enable models to **adapt at inference time** to domain shifts and unseen data distributions, without requiring access to source training data.

---

## 🔍 Motivation

Deep neural networks often struggle when test data differs from the training distribution (domain shift). 
In real-world applications such as **physical security, surveillance, and embedded analytics**, models must remain **robust, adaptive, and reliable** despite changes in conditions. 

**Test-Time Adaptation** addresses this challenge by updating the model (or part of it) *on the fly*, using only information available at inference time.

---

## 🏗️ Approaches

This repo covers concepts and references on: 
- **Entropy minimization** and self-supervised objectives for TTA 
- **Batch norm adaptation** under distribution shifts 
- **Online adaptation vs. episodic adaptation** 
- **Efficiency for embedded systems**: ensuring adaptation is lightweight and resource-aware 
- **Reliability**: strategies to maintain stability and avoid catastrophic drift 

---

## 📚 Publications & References

My contributions in this field are connected to ongoing research in **robust and adaptive AI**: 

- [**DART^3: Leveraging Distance for Test Time Adaptation in Person Re-Identification**](https://arxiv.org/abs/2505.18337) - preprint 2025

- Related: [**EXaM: Unsupervised Concept-Based Representation Learning to Better Explain Models in Vision Tasks**](https://scholar.google.com/citations?view_op=view_citation&hl=fr&user=OBIkP1AAAAAJ&citation_for_view=OBIkP1AAAAAJ:Tyk-4Ss8FVUC) – *XAI4CV, CVPR 2025 (Spotlight)* 

For background, see: 
- Tent: Fully Test-Time Adaptation by Entropy Minimization (ICLR 2021) 
- Source-Free Test-Time Adaptation Survey (arXiv 2022) 

---

## 🚀 Repository Content

> ⚠️ Note: Industrial implementations are not shared here due to IP restrictions. This repo focuses on **research concepts, references, and illustrative notes**.

---

## 📫 Contact

- [LinkedIn](https://www.linkedin.com/in/maguelonne-heritier-03ba9bb)
- [Google Scholar](https://scholar.google.com/citations?user=OBIkP1AAAAAJ&hl=fr&oi=ao) 

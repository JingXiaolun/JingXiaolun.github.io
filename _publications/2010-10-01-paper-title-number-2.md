---
title: "TC-MGC: Text-Conditioned Multi-Grained Contrastive Learning for Text–Video Retrieval"
collection: publications
category: manuscripts
permalink: /publication/2010-10-01-paper-title-number-2
excerpt: 'In this paper, we propose a novel Text-Conditioned Multi-Grained Contrast (TCMGC) framework to explore multi-grained contrasts between textual
and semantic-relevant visual representations.'
date: 2025-03-23
venue: 'Journal Of Information Fusion'
paperurl: 'https://doi.org/10.1016/j.inffus.2025.103151'
citation: 'Xiaolun Jing, Genke Yang, Jian Chu. TC-MGC: Text-conditioned multi-grained contrastive learning for text-video retrieval[J]. Information Fusion, 2025, 121:103151.'
---

## Abstract
Motivated by the success of coarse-grained or fine-grained contrast in text–video retrieval, there emerge
multi-grained contrastive learning methods which focus on the integration of contrasts with different granularity. However, due to the wider semantic range of videos, the text-agnostic video representations might
encode misleading information not described in texts, thus impeding the model from capturing precise
cross-modal semantic correspondence. To this end, we propose a Text-Conditioned Multi-Grained Contrast
framework, dubbed TC-MGC. Specifically, our model employs a language–video attention block to generate
aggregated frame and video representations conditioned on the word’s and text’s attention weights over
frames. To filter unnecessary similarity interactions and decrease trainable parameters in the Interactive
Similarity Aggregation (ISA) module, we design a Similarity Reorganization (SR) module to identify attentive
similarities and reorganize cross-modal similarity vectors and matrices. Next, we argue that the imbalance
problem among multi-grained similarities may result in over- and under-representation issues. We thereby
introduce an auxiliary Similarity Decorrelation Regularization (SDR) loss to facilitate cooperative relationship
utilization by similarity variance minimization on matching text–video pairs. Finally, we present a Linear
Softmax Aggregation (LSA) module to explicitly encourage the interactions between multiple similarities and
promote the usage of multi-grained information. Empirically, TC-MGC achieves competitive results on multiple
text–video retrieval benchmarks, outperforming X-CLIP model by +2.8% (+1.3%), +2.2% (+1.0%), +1.5%
(+0.9%) relative (absolute) improvements in text-to-video retrieval R@1 on MSR-VTT, DiDeMo and VATEX,
respectively. Our code is publicly available at https://github.com/JingXiaolun/TC-MGC.

## Key words
Language–video attention; Linear Softmax Aggregation; Similarity Decorrelation Regularization; Similarity reorganization; Text–video retrieval

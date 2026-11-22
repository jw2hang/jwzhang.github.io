---
title: "Understanding Why Language Models Hallucinate: Testing Reasoning Against Priors"
date: 2026-08-01
publishDate: 2026-08-01
authors: ["Yangfan Hu", "Xuhan Tong", "Haoyue Bai", "Xi Ding", "Shashank Muralidhar Bharadwaj", "Siyang Cao", "Robert Nowak", "Jiawei Zhang"]
publication_types: ["1"]
abstract: "Large language models often produce hallucinated answers that violate prompt-level constraints. A key diagnostic question is whether these failures reflect missing knowledge, or whether the model has the relevant information but follows the wrong inference path. We study this phenomenon as inference misalignment: a mismatch between the answer supported by the prompt and the answer favored by statistically salient latent associations. We formalize this view with a latent key-task model, in which pretraining-frequency imbalance can cause a shortcut path to dominate the constraint-sensitive path and induce positive inference loss. The framework predicts two failure modes: task-retrieval bias in entity disambiguation and key-selection bias in action choice. We introduce TrapQA, a controlled diagnostic testbed with two components. ScientistQA tests disambiguation among similar scientists with supplementary factual probes, while Real-Life Constrained QA tests everyday constraint following under salient shortcuts. Our results show that hallucination can arise from biased latent inference rather than absent knowledge alone."
featured: false
publication: "*Findings of the Association for Computational Linguistics: EMNLP 2026*"
---

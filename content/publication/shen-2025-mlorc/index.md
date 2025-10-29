---
title: "MLorc: Momentum Low-rank Compression for Large Language Model Adaptation
"
date: 2025-06-02
publishDate: 2025-06-02
authors: ["Wei Shen", "Zhang Yaxiang", "Minhui Huang", "Mengfan Xu", "Jiawei Zhang", "Cong Shen"]
publication_types: ["3"]
abstract: "With increasing size of large language models (LLMs), full-parameter fine-tuning imposes substantial memory demands. To alleviate this, we propose a novel memory-efficient training paradigm called Momentum Low-rank compression (MLorc). The key idea of MLorc is to compress and reconstruct the momentum of matrix parameters during training to reduce memory consumption. Compared to LoRA, MLorc avoids enforcing a fixed-rank constraint on weight update matrices and thus enables full-parameter learning. Compared to GaLore, MLorc directly compress the momentum rather than gradients, thereby better preserving the training dynamics of full-parameter fine-tuning. We provide a theoretical guarantee for its convergence under mild assumptions. Empirically, MLorc consistently outperforms other memory-efficient training methods, matches or even exceeds the performance of full fine-tuning at small ranks (e.g., r=4), and generalizes well across different optimizers -- all while not compromising time or memory efficiency."
featured: false
publication: "*arXiv preprint arXiv:2506.01897*"
---

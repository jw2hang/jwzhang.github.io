---
title: "When the Wrong Key Wins: Understanding and Detecting Hallucinations in LLMs"
date: 2026-09-14
publishDate: 2026-09-14
authors: ["Xuhan Tong", "Haoyue Bai", "Dawei Zhou", "Naichen Shi", "Jiawei Zhang"]
publication_types: ["3"]
abstract: "Large language models can hallucinate even when the knowledge required for a correct answer is already available. We study this failure through a latent-key view of inference, where answer selection depends on competition among associations acquired during pretraining. We show that model predictions can be highly sensitive to individual query keywords, that these influential keywords exhibit entity-specific binding, and that their effects are systematically shaped by pretraining frequency. Multiple bindings can also compete and exhibit higher-order interactions within the same query. Based on this mechanism, we introduce a two-stage keyword-perturbation method for hallucination detection. By removing influential keywords and measuring how the model reorganizes its prediction, the method distinguishes errors caused by misleading key associations from correct decisions supported by diagnostic evidence. Across multiple models and benchmarks, perturbation provides a strong and transferable detection signal, reaching $0.910$ AUROC on probe-known ScientistQA. Finally, we extend the same probabilistic framework to four hallucination regimes: knowledge deficit, wrong knowledge, context distraction, and unstable inference. Their operational distributions across benchmarks provide diagnostic context for why different detector families succeed in different settings."
featured: false
publication: "*arXiv preprint arXiv:2609.15106*"
---

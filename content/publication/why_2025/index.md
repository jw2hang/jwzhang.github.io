---
title: "Why GRPO Needs Normalization: A Local-Curvature Perspective on Adaptive Gradients"
date: 2026-01-30
publishDate: 2026-01-30
authors: ["Cheng Ge", "Caitlyn Heqi Yin", "Hao Liang", "Jiawei Zhang"]
publication_types: ["3"]
abstract: "Reinforcement learning (RL) has become a key driver of language model reasoning. Among RL algorithms, Group Relative Policy Optimization (GRPO) is the de facto standard, avoiding the need for a critic by using per-prompt baselines and variance normalization. Yet why and when this normalization helps remains unclear. In this work, we answer both questions through the lens of local curvature of the sequence-level policy gradient: standard deviation normalization implements an adaptive gradient. Theoretically, we prove that under mild conditions GRPO attains an improved convergence rate over unnormalized REINFORCE, with gains characterized by the average within-prompt reward standard deviation across prompts and iterations. We further introduce IS-GRPO, an importance-sampling variant of GRPO whose expected update remains aligned with the full gradient, and prove a convergence guarantee of the same form as REINFORCE's, which is tighter in practice during real training runs by a factor we measure. Empirically, on GSM8K and MATH we validate the curvature--variance link and measure the quantities that govern our bounds along real training runs. At 1.5B scale, per-prompt normalization outperforms both unnormalized and globally normalized baselines, with gains that emerge in a middle phase of training where per-prompt variances become heterogeneous. At 7B scale, the normalization schemes become statistically indistinguishable while IS-GRPO retains a small lead, in line with the theory's prediction that the gains require heterogeneity."
featured: false
publication: "*arXiv preprint arXiv:2601.23135*"
---

---
title: "When Expressivity Meets Trainability: Fewer than $n$ Neurons Can Work"
date: 2021-01-01
publishDate: 2023-06-12T09:48:22.163850Z
authors: ["Jiawei Zhang", "Yushun Zhang", "Mingyi Hong", "Ruoyu Sun", "Zhi-Quan Luo"]
publication_types: ["1"]
abstract: "Modern neural networks are often quite wide, causing large memory and computation costs. It is thus of great interest to train a narrower network. However, training narrow neural nets remains a challenging task. We ask two theoretical questions: Can narrow networks have as strong expressivity as wide ones? If so, does the loss function exhibit a benign optimization landscape? In this work, we provide partially affirmative answers to both questions for 1-hidden-layer networks with fewer than $n$ (sample size) neurons when the activation is smooth. First, we prove that as long as the width $m geq 2n/d$ (where $d$ is the input dimension), its expressivity is strong, ie, there exists at least one global minimizer with zero training loss. Second, we identify a nice local region with no local-min or saddle points. Nevertheless, it is not clear whether gradient descent can stay in this nice region. Third, we consider a constrained optimization formulation where the feasible region is the nice local region, and prove that every KKT point is a nearly global minimizer. It is expected that projected gradient methods converge to KKT points under mild technical conditions, but we leave the rigorous convergence analysis to future work. Thorough numerical results show that projected gradient methods on this constrained formulation significantly outperform SGD for training narrow neural nets."
featured: false
publication: "*Advances in Neural Information Processing Systems 34 (NeurIPS 2021)*"
---


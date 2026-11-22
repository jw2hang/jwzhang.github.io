---
title: "A Single-Loop First-Order Algorithm for Linearly Constrained Bilevel Optimization"
date: 2025-12-01
publishDate: 2025-12-01
authors: ["Wei Shen", "Jiawei Zhang", "Minhui Huang", "Cong Shen"]
publication_types: ["1"]
abstract: "We study bilevel optimization problems where the lower-level problems are strongly convex and have coupled linear constraints. To overcome the potential non-smoothness of the hyper-objective and the computational challenges associated with the Hessian matrix, we utilize penalty and augmented Lagrangian methods to reformulate the original problem as a single-level one. Especially, we establish a strong theoretical connection between the reformulated function and the original hyper-objective by characterizing the closeness of their values and derivatives. Based on this reformulation, we propose a single-loop, first-order algorithm for linearly constrained bilevel optimization (SFLCB). We provide rigorous analyses of its non-asymptotic convergence rates, showing an improvement over prior double-loop algorithms -- form $O(ε^{-3}\\log(ε^{-1}))$ to $O(ε^{-3})$. The experiments corroborate our theoretical findings and demonstrate the practical efficiency of the proposed SFLCB algorithm. Simulation code is provided at https://github.com/ShenGroup/SFLCB."
featured: false
publication: "*Advances in Neural Information Processing Systems 38 (NeurIPS 2025)*"
---

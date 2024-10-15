---
title: "A Proximal Alternating Direction Method of Multiplier for Linearly Constrained Nonconvex Minimization"
date: 2020-01-01
publishDate: 2023-06-12T09:48:22.157489Z
authors: ["Jiawei Zhang", "Zhi-Quan Luo"]
publication_types: ["2"]
abstract: "Consider the minimization of a nonconvex differentiable function over a bounded polyhedron. A popular primal-dual first-order method for this problem is to perform a gradient projection iteration for the augmented Lagrangian function and then update the dual multiplier vector using the constraint residual. However, numerical examples show that this approach can exhibit “oscillation” and may not converge. In this paper, we propose a proximal alternating direction method of multipliers for the multiblock version of this problem. A distinctive feature of this method is the introduction of a “smoothed” (i.e., exponentially weighted) sequence of primal iterates and the inclusion, at each iteration, to the augmented Lagrangian function of a quadratic proximal term centered at the current smoothed primal iterate. The resulting proximal augmented Lagrangian function is inexactly minimized (via a gradient projection step) at each iteration while the dual multiplier vector is updated using the residual of the linear constraints. When the primal and dual stepsizes are chosen sufficiently small, we show that suitable “smoothing” can stabilize the “oscillation,” and the iterates of the new proximal ADMM algorithm converge to a stationary point under some mild regularity conditions. The iteration complexity of our algorithm for finding an $epsilon$-stationary solution is $O(1/epsilon^2)$, which improves the best known complexity of $O(1/epsilon^3)$ for the problem under consideration. Furthermore, when the objective function is quadratic, we establish the linear convergence of the algorithm. Our proof is based on a new potential function and a novel use of error bounds."
featured: false
publication: "*SIAM Journal on Optimization*"
---


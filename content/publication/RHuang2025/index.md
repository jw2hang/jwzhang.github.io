---
title: "Stochastic Smoothed Primal-Dual Algorithms for Nonconvex Optimization with Linear Inequality Constraints"
date: 2025-05-26
publishDate: 2025-05-26
authors: ["Ruichuan Huang", "Jiawei Zhang", "Ahmet Alacaoglu"]
publication_types: ["1"]
abstract: "We propose smoothed primal-dual algorithms for solving stochastic and smooth nonconvex optimization problems with linear inequality constraints. Our algorithms are single-loop and only require a single stochastic gradient based on one sample at each iteration. A distinguishing feature of our algorithm is that it is based on an inexact gradient descent framework for the Moreau envelope, where the gradient of the Moreau envelope is estimated using one step of a stochastic primal-dual augmented Lagrangian method. To handle inequality constraints and stochasticity, we combine the recently established global error bounds in constrained optimization with a Moreau envelope-based analysis of stochastic proximal algorithms. For obtaining ε-stationary points, we establish the optimal O(ε−4) sample complexity guarantee for our algorithms and provide extensions to stochastic linear constraints. We also show how to improve this complexity to O(ε−3) by using variance reduction and the expected smoothness assumption. Unlike existing methods, the iterations of our algorithms are free of subproblems, large batch sizes or increasing penalty parameters and use dual variable updates to ensure feasibility."
featured: false
publication: "*International Conference on Machine Learning (ICML 2025)*"
---
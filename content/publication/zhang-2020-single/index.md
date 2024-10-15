---
title: "A Single-Loop Smoothed Gradient Descent-Ascent Algorithm for Nonconvex-Concave Min-Max Problems"
date: 2020-01-01
publishDate: 2023-06-12T09:48:22.162124Z
authors: ["Jiawei Zhang", "Peijun Xiao", "Ruoyu Sun", "Zhiquan Luo"]
publication_types: ["1"]
abstract: "Nonconvex-concave min-max problem arises in many machine learning applications including minimizing a pointwise maximum of a set of nonconvex functions and robust adversarial training of neural networks. A popular approach to solve this problem is the gradient descent-ascent (GDA) algorithm which unfortunately can exhibit oscillation in case of nonconvexity. In this paper, we introduce a $smoothing$ scheme which can be combined with GDA to stabilize the oscillation and ensure convergence to a stationary solution. We prove that the stabilized GDA algorithm can achieve an $O(1/epsilon^2)$ iteration complexity for minimizing the pointwise maximum of a finite collection of nonconvex functions. Moreover, the smoothed GDA algorithm achieves an $O(1/epsilon^4)$ iteration complexity for general nonconvex-concave problems. Extensions of this stabilized GDA algorithm to multi-block cases are presented. To the best of our knowledge, this is the first algorithm to achieve $O(1/epsilon^2)$ for a class of nonconvex-concave problem. We illustrate the practical efficiency of the stabilized GDA algorithm on robust training."
featured: false
publication: "*Advances in Neural Information Processing Systems 33 (NeurIPS 2020)*"
---


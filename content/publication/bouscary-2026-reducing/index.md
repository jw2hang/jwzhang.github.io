---
title: "Reducing Contextual Stochastic Bilevel Optimization via Structured Function Approximation"
date: 2026-04-01
publishDate: 2026-04-01
authors: ["Maxime Bouscary", "Jiawei Zhang", "Saurabh Amin"]
publication_types: ["1"]
abstract: "Contextual Stochastic Bilevel Optimization (CSBO) extends standard stochastic bilevel optimization (SBO) by incorporating context-dependent lower-level problems. CSBO problems are generally intractable since existing methods require solving a distinct lower-level problem for each sampled context, resulting in prohibitive sample and computational complexity, in addition to relying on impractical conditional sampling oracles. We propose a reduction framework that approximates the lower-level solutions using expressive basis functions, thereby decoupling the lower-level dependence on context and transforming CSBO into a standard SBO problem solvable using only joint samples from the context and noise distribution. First, we show that this reduction preserves hypergradient accuracy and yields an $ε$-stationary solution to CSBO. Then, we relate the sample complexity of the reduced problem to simple metrics of the basis. This establishes sufficient criteria for a basis to yield $ε$-stationary solutions with a near-optimal complexity of $\\widetilde{O}(ε^{-3})$, matching the best-known rate for standard SBO up to logarithmic factors. Moreover, we show that Chebyshev polynomials provide a concrete and efficient choice of basis that satisfies these criteria for a broad class of problems. Empirical results on inverse and hyperparameter optimization demonstrate that our approach outperforms CSBO baselines in convergence, sample efficiency, and memory usage."
featured: false
publication: "*International Conference on Learning Representations (ICLR 2026)*"
---

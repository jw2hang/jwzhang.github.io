---
title: "From Likelihood Convergence to Parameter Convergence in POMDPs"
date: 2026-09-01
publishDate: 2026-09-01
authors: ["Jack Zhang", "Saurabh Amin", "Jiawei Zhang", "Patrick Jaillet"]
publication_types: ["1"]
abstract: "Likelihood-based methods are widely used to learn the parameters of partially observable Markov decision processes (POMDPs). While finite-sample guarantees for policy suboptimality exist for certain POMDP subclasses, analogous guarantees for parameter recovery remain less well understood. For any candidate POMDP parameter, we bound its parameter recovery error in terms of its likelihood gap to the ground truth, the structural conditioning of the observation and transition kernels, and the behavior policy used to collect data. The bound applies in both the undercomplete and overcomplete regimes, with the latter following naturally from the undercomplete analysis. Because the result applies to any sufficiently good candidate, it yields finite-sample guarantees for the maximum-likelihood estimator and any procedure producing a parameter with controlled likelihood gap. This is particularly useful for near-optimal learning in infinite-horizon POMDPs, where existing approaches largely rely on model-based planning with accurate transition and observation kernel estimates. The bound separates the contributions of the behavior policy and model, showing how data-collection choices, including action coverage, and their effects on mixing can accelerate parameter learning."
featured: false
publication: "*Advances in Neural Information Processing Systems 39 (NeurIPS 2026)*"
---

---
title: "An Optimization Framework for Denoising Generation"
date: 2026-11-17
publishDate: 2026-11-17
authors: ["Xinyu Zhou", "Jiawei Zhang", "Stephen J. Wright"]
publication_types: ["3"]
abstract: "Noise-unconditioned denoising learns a single score, so generation can be viewed as gradient ascent on a fixed log-density landscape. This optimization interpretation leaves two questions: do trajectories approach meaningful data, and do different initializations retain diverse outcomes? We establish both phenomena for empirical and population multi-scale Gaussian-mixture objectives. Under explicit posterior and landscape conditions, ascent converges almost surely within $O(mσ_{\\min}^2/τ)$ of an $m$-dimensional reference manifold with reach at least $τ$. We derive a source--sink identity for the same fixed field and use it to prove finite-resolution regional coverage. In an affine construction, we further identify a positive-bandwidth regime where even empirical-score optimization can avoid training-sample memorization while preserving diversity at the training resolution. The same fixed objective naturally supports penalty-guided controllable generation. Experiments support our predicted mechanisms, show improved robustness under large-step guidance, and demonstrate downstream gains consistent with finite-data generative generalization."
featured: false
publication: "*arXiv preprint arXiv:2611.22202*"
---

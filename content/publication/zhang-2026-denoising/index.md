---
title: "Denoising as Projection: Constrained Optimization with Gradient-Guided Diffusion"
date: 2026-08-30
publishDate: 2026-08-30
authors: ["Runyu Zhang", "Jiawei Zhang", "Gioele Zardini", "Saurabh Amin", "Asuman Ozdaglar"]
publication_types: ["3"]
abstract: "Diffusion models are increasingly used not only for sampling from learned data distributions, but also for generating samples that optimize task-specific objectives. A common approach is to guide the reverse diffusion process using gradients of an external objective. However, when the data distribution is supported on a structured feasible set, such as a manifold or a constraint set, gradient guidance can move samples away from the learned data geometry. In this paper, we study a simple projected-gradient-guided diffusion update based on the observation that the Stein denoising operator can act as an approximate projection onto the data geometry. The proposed update incorporates the objective gradient inside the denoising step, yielding an inference-time method that uses only a pretrained denoiser and gradient evaluations. We analyze this update as an inexact projected-gradient method for constrained optimization over learned feasible geometries. Our theory covers three settings: linear manifolds, compact convex feasible sets, and compact Riemannian submanifolds. In all these settings, we prove descent and finite-time convergence guarantees. Numerical experiments support the theoretical interpretation and illustrate how the proposed update balances objective descent with preservation of the learned geometry."
featured: false
publication: "*arXiv preprint arXiv:2608.29507*"
---

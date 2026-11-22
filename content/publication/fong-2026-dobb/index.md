---
title: "Dobb: Shard-Local Preconditioning in Block-Diagonal Eigenbases"
date: 2026-10-29
publishDate: 2026-10-29
authors: ["Shi-Yuk Fong", "Shuhua Yu", "Jiawei Zhang"]
publication_types: ["3"]
abstract: "Training language models whose parameters and optimizer state exceed a single node's memory requires sharding these tensors across devices. Under tensor parallelism (TP) or fully sharded data parallelism (FSDP), matrix-aware optimizers such as Muon introduce communication to perform global matrix operations across shards. We propose Dobb (Distributed Optimizer with Block-diagonal Eigenbases), a matrix-aware optimizer designed to compute updates locally within parameter shards. Dobb approximates the input-activation second moment with diagonal blocks and tracks a complete basis within each block. It projects momentum into these bases, applies sign normalization to the coefficients, and reconstructs the update. When each block lies within one shard under TP or FSDP, Dobb applies its matrix update locally, requiring no communication beyond data-parallel synchronization of the activation second moments. We benchmark Dobb against Dion, a distributed matrix-aware optimizer designed to retain the benefits of orthonormalized updates while reducing communication. On GPT-2 XL (1.56B parameters), Dobb with 16 blocks reaches a validation loss of 2.476, compared with 2.511 for Dion at rank fraction 1/16. Under FSDP on 32 H100 GPUs, Dobb reduces the amortized optimizer-call time from 124.1 ms for Dion to 9.2 ms."
featured: false
publication: "*arXiv preprint arXiv:2610.39412*"
---

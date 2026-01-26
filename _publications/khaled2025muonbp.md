---
title: 'MuonBP: Faster Muon via Block-Periodic Orthogonalization'
collection: publications
category: manuscripts
permalink: /publication/khaled2025muonbp
excerpt: #''
date: 2025-10-19
venue: 'arXiv preprint arXiv:2510.16981'
link: 'https://arxiv.org/abs/2510.16981'
paperurl: 'https://arxiv.org/abs/2510.16981'
citation: 'Ahmed Khaled, Kaan Ozkara, <strong>Tao Yu</strong>, Mingyi Hong, Youngsuk Park.'
---

Gradient orthogonalization is a simple strategy that shows great utility in speeding up gradient descent. The Muon optimizer (Jordan, Jin, et al., 2024) combines gradient orthogonalization with first-order momentum and achieves significant improvement in data efficiency over Adam/AdamW (Loshchilov and Hutter, 2019) for language model training. However, when using model parallelism, gradient orthogonalization introduces additional overhead compared to coordinate-wise optimizers (such as AdamW) due to additional gather and scatter operations on gradient matrix shards from different devices. This additional communication can amount to a throughput hit of 5%-10% compared to Adam/AdamW. To remedy this, we propose Muon with Block-Periodic Orthogonalization (MuonBP), which applies orthogonalization independently to matrix shards on each device and periodically performs full orthogonalization to maintain training stability at scale. We show how to adjust the learning rate from the baseline to MuonBP and give convergence guarantees for this algorithm. Crucially, our theory dictates that we use two stepsizes: one for the blockwise orthogonalization steps, and one for the full orthogonalization steps. Our method is simple, requires minimal hyperparameter adjustments, and achieves competitive iteration complexity compared with baseline Muon while providing per-iteration throughput comparable to coordinate-wise methods such as AdamW. When training an 8B model with eight-way tensor parallelism and ZeRO optimizer state sharding, MuonBP achieves 8% throughput increase compared to Muon with no degradation in performance.

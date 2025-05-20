---
title: "Random Laplacian Features For Learning with Hyperbolic Space"
collection: publications
category: conferences
permalink: /publication/yu2022random
excerpt: #''
date: 2023-01-01
venue: '11th International Conference on Learning Representations (ICLR 2023)'
link: 'https://arxiv.org/abs/2202.06854'
paperurl: 'https://arxiv.org/abs/2202.06854'
codeurl: 'https://github.com/ydtydr/HyLa'
citation: '<strong>Tao Yu</strong>, Christopher De Sa.'
---

Due to its geometric properties, hyperbolic space can support high-fidelity embeddings of tree- and graph-structured data, upon which various hyperbolic networks have been developed. Existing hyperbolic networks encode geometric priors not only for the input, but also at every layer of the network. This approach involves repeatedly mapping to and from hyperbolic space, which makes these networks complicated to implement, computationally expensive to scale, and numerically unstable to train. In this paper, we propose a simpler approach: learn a hyperbolic embedding of the input, then map once from it to Euclidean space using a mapping that encodes geometric priors by respecting the isometries of hyperbolic space, and finish with a standard Euclidean network. The key insight is to use a random feature mapping via the eigenfunctions of the Laplace operator, which we show can approximate any isometry-invariant kernel on hyperbolic space. Our method can be used together with any graph neural networks: using even a linear graph model yields significant improvements in both efficiency and performance over other hyperbolic baselines in both transductive and inductive tasks.

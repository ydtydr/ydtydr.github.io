---
title: "Numerically Accurate Hyperbolic Embeddings Using Tiling-Based Models"
collection: publications
category: conferences
permalink: /publication/yu2019numerically
excerpt: #''
date: 2019-01-03
venue: '33rd Conference on Neural Information Processing Systems (NeurIPS 2019 <strong>Spotlight</strong>)'
link: 'https://proceedings.neurips.cc/paper/2019/hash/82c2559140b95ccda9c6ca4a8b981f1e-Abstract.html'
paperurl: 'https://proceedings.neurips.cc/paper/2019/hash/82c2559140b95ccda9c6ca4a8b981f1e-Abstract.html'
codeurl: 'https://github.com/ydtydr/HyperbolicTiling_Compression'
codeurlalt: 'https://github.com/ydtydr/HyperbolicTiling_Learning'
citation: '<strong>Tao Yu</strong>, Christopher De Sa.'
---

Hyperbolic embeddings achieve excellent performance when embedding hierarchical data structures like synonym or type hierarchies, but they can be limited by numerical error when ordinary floating-point numbers are used to represent points in hyperbolic space. Standard models such as the Poincar{\'e} disk and the Lorentz model have unbounded numerical error as points get far from the origin. To address this, we propose a new model which uses an integer-based tiling to represent \emph{any} point in hyperbolic space with provably bounded numerical error. This allows us to learn high-precision embeddings without using BigFloats, and enables us to store the resulting embeddings with fewer bits. We evaluate our tiling-based model empirically, and show that it can both compress hyperbolic embeddings (down to 2% of a Poincar{\'e} embedding on WordNet Nouns) and learn more accurate embeddings on real-world datasets.

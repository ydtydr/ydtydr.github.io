---
title: "Representing Hyperbolic Space Accurately using Multi-Component Floats"
collection: publications
category: conferences
permalink: /publication/yu2021representing
excerpt: #''
date: 2021-01-01
venue: '35th Conference on Neural Information Processing Systems (NeurIPS 2021)'
link: 'https://proceedings.neurips.cc/paper_files/paper/2021/hash/832353270aacb6e3322f493a66aaf5b9-Abstract.html'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2021/hash/832353270aacb6e3322f493a66aaf5b9-Abstract.html'
citation: '<strong>Tao Yu</strong>, Christopher De Sa.'
---

Hyperbolic space is particularly useful for embedding data with hierarchical structure; however, representing hyperbolic space with ordinary floating-point numbers greatly affects the performance due to its \emph{ineluctable} numerical errors. Simply increasing the precision of floats fails to solve the problem and incurs a high computation cost for simulating greater-than-double-precision floats on hardware such as GPUs, which does not support them. In this paper, we propose a simple, feasible-on-GPUs, and easy-to-understand solution for numerically accurate learning on hyperbolic space. We do this with a new approach to represent hyperbolic space using multi-component floating-point (MCF) in the Poincar{\'e} upper-half space model. Theoretically and experimentally we show our model has small numerical error, and on embedding tasks across various datasets, models represented by multi-component floating-points gain more capacity and run significantly faster on GPUs than prior work.

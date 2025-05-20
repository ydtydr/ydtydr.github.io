---
title: "Coneheads: Hierarchy Aware Attention"
collection: publications
category: conferences
permalink: /publication/tseng2023coneheads
excerpt: #''
date: 2023-01-02
venue: '37th Conference on Neural Information Processing Systems (NeurIPS 2023)'
link: 'https://proceedings.neurips.cc/paper_files/paper/2023/hash/a17251f8d595179eef5e466b1f5f7a85-Abstract-Conference.html'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2023/hash/a17251f8d595179eef5e466b1f5f7a85-Abstract-Conference.html'
codeurl: 'https://github.com/tsengalb99/coneheads'
citation: 'Albert Tseng, <strong>Tao Yu</strong>, Toni J.B. Liu, Christopher De Sa.'
---

Attention networks such as transformers have achieved state-of-the-art performance in many domains. These networks rely heavily on the dot product attention operator, which computes the similarity between two points by taking their inner product. However, the inner product does not explicitly model the complex structural properties of real world datasets, such as hierarchies between data points. To remedy this, we introduce cone attention, a drop-in replacement for dot product attention based on hyperbolic entailment cones. Cone attention associates two points by the depth of their lowest common ancestor in a hierarchy defined by hyperbolic cones, which intuitively measures the divergence of two points and gives a 
hierarchy aware similarity score. We test cone attention on a wide variety of models and tasks and show that it improves task-level performance over dot product attention and other baselines, and is able to match dot-product attention with significantly fewer parameters. Our results suggest that cone attention is an effective way to capture hierarchical relationships when calculating attention.

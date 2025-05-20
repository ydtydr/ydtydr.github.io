---
title: 'MCTensor: A High-Precision Deep Learning Library with Multi-Component Floating-Point'
collection: publications
category: workshops
permalink: /publication/yu2022mctensor
excerpt: #''
date: 2022-01-01
venue: 'Workshop on Hardware Aware Eﬃcient Training (HAET-ICML 2022)'
link: 'https://arxiv.org/abs/2207.08867'
paperurl: 'https://arxiv.org/abs/2207.08867'
codeurl: 'https://github.com/ydtydr/MCTensor'
citation: '<strong>Tao Yu</strong>, Wentao Guo, Jianan Canal Li, Tiancheng Yuan, Christopher De Sa.'
---

In this paper, we introduce MCTensor, a library based on PyTorch for providing general-purpose and high-precision arithmetic for DL training. MCTensor is used in the same way as PyTorch Tensor: we implement multiple basic, matrix-level computation operators and NN modules for MCTensor with identical PyTorch interface. Our algorithms achieve high precision computation and also benefits from heavily-optimized PyTorch floating-point arithmetic. We evaluate MCTensor arithmetic against PyTorch native arithmetic for a series of tasks, where models using MCTensor in float16 would match or outperform the PyTorch model with float32 or float64 precision.

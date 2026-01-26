---
title: 'Scaling Laws Meet Model Architecture: Toward Inference-Efficient LLMs'
collection: publications
category: conferences
permalink: /publication/bian2025scaling
excerpt: #''
date: 2025-10-21
venue: '[Accepted to] 14th International Conference on Learning Representations (ICLR 2026)'
link: 'https://arxiv.org/abs/2510.18245'
paperurl: 'https://arxiv.org/abs/2510.18245'
citation: 'Song Bian, <strong>Tao Yu</strong>, Shivaram Venkataraman, Youngsuk Park.'
---

Scaling the number of parameters and the size of training data has proven to be an effective strategy for improving large language model (LLM) performance. Yet, as these models grow increasingly powerful and widely deployed, the cost of inference has become a pressing concern. Despite its importance, the trade-off between model accuracy and inference efficiency remains underexplored. In this work, we examine how key architectural factors, hidden size, the allocation of parameters between MLP and attention (mlp-to-attention ratio), and grouped-query attention (GQA), influence both inference cost and accuracy. We introduce a conditional scaling law that augments the Chinchilla framework with architectural information, along with a search framework for identifying architectures that are simultaneously inference-efficient and accurate. To validate our approach, we train more than 200 models spanning 80M to 3B parameters and 8B to 100B training tokens, and fit the proposed conditional scaling law. Our results show that the conditional scaling law reliably predicts optimal architectural choices and that the resulting models outperform existing open-source baselines. Under the same training budget, optimized architectures achieve up to 2.1% higher accuracy and 42% greater inference throughput compared to LLaMA-3.2.
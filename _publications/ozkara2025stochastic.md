---
title: 'Stochastic Rounding for LLM Training: Theory and Practice'
collection: publications
category: conferences
permalink: /publication/ozkara2025stochastic
excerpt: #''
date: 2025-01-01
venue: '28th International Conference on Artificial Intelligence and Statistics (AISTATS 2025)'
link: 'https://proceedings.mlr.press/v258/ozkara25b.html'
paperurl: 'https://proceedings.mlr.press/v258/ozkara25b.html'
codeurl: 'https://github.com/amazon-science/adamw-sr'
citation: 'Kaan Ozkara, <strong>Tao Yu</strong>, Youngsuk Park.'
---

As the parameters of Large Language Models (LLMs) have scaled to hundreds of billions, the demand for efficient training methods—balancing faster computation and reduced memory usage without sacrificing accuracy—has become more critical than ever. In recent years, various mixed precision strategies, which involve different precision levels for optimization components, have been proposed to increase training speed with minimal accuracy degradation. However, these strategies often require manual adjustments and lack theoretical justification. In this work, we leverage stochastic rounding (SR) to address numerical errors of training with low-precision representation. We provide theoretical analyses of implicit regularization and convergence under the Adam optimizer when SR is utilized. With the insights from these analyses, we extend previous BF16 + SR strategy to be used in distributed settings, enhancing the stability and performance for large scale training. Empirical results from pre-training models with up to 6.7B parameters, for the first time, demonstrate that our BF16 with SR strategy outperforms (BF16, FP32) mixed precision strategies, achieving better validation perplexity, up to 1.54× higher throughput, and 30% lower memory usage.

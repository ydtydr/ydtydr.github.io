---
title: "Collage: Light-Weight Low-Precision Strategy for LLM Training"
collection: publications
category: conferences
permalink: /publication/yu2024collage
excerpt: #''
date: 2024-01-02
venue: '41th International Conference on Machine Learning (ICML 2024)'
link: 'https://proceedings.mlr.press/v235/yu24d.html'
paperurl: 'https://proceedings.mlr.press/v235/yu24d.html'
codeurl: 'https://github.com/amazon-science/collage'
citation: '<strong>Tao Yu</strong>, Gaurav Gupta, Karthick Gopalswamy, Amith R Mamidala, et al.'
---

Large models training is plagued by the intense compute cost and limited hardware memory. A practical solution is low-precision representation but is troubled by loss in numerical accuracy and unstable training rendering the model less useful. We argue that low-precision floating points can perform well provided the error is properly compensated at the critical locations in the training process. We propose Collage which utilizes multi-component float representation in low-precision to accurately perform operations with numerical errors accounted. To understand the impact of imprecision to training, we propose a simple and novel metric which tracks the lost information during training as well as differentiates various precision strategies. Our method works with commonly used low-precision such as half-precision (16-bit floating points) and can be naturally extended to work with even lower precision such as 8-bit. Experimental results show that pre-training using Collage removes the requirement of using 32-bit floating-point copies of the model and attains similar/better training performance compared to (16,32)-bit mixed-precision strategy, with up to 3.7× speedup and ∼15% to 23% less memory usage in practice. 

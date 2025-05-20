---
title: 'Training LLMs with MXFP4'
collection: publications
category: conferences
permalink: /publication/tseng2025training
excerpt: #''
date: 2025-01-02
venue: '28th International Conference on Artificial Intelligence and Statistics (AISTATS 2025)'
link: 'https://proceedings.mlr.press/v258/tseng25a.html'
paperurl: 'https://proceedings.mlr.press/v258/tseng25a.html'
codeurl: 'https://github.com/amazon-science/mxfp4-llm'
citation: 'Albert Tseng, <strong>Tao Yu</strong>, Youngsuk Park.'
---

Low precision (LP) datatypes such as MXFP4 can accelerate matrix multiplications (GEMMs) and reduce training costs. However, directly using MXFP4 instead of BF16 during training significantly degrades model quality. In this work, we present the first near-lossless training recipe that uses MXFP4 GEMMs, which are 2× faster than FP8 on supported hardware. Our key insight is to compute unbiased gradient estimates with stochastic rounding (SR), resulting in more accurate model updates. However, directly applying SR to MXFP4 can result in high variance from block-level outliers, harming convergence. To overcome this, we use the random Hadamard tranform to theoretically bound the variance of SR. We train GPT models up to 6.7B parameters and find that our method induces minimal degradation over mixed-precision BF16 training. Our recipe computes >1/2 the training FLOPs in MXFP4, enabling an estimated speedup of >1.3× over FP8 and >1.7× over BF16 during backpropagation.

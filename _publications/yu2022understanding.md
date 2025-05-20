---
title: "Understanding Hyperdimensional Computing for Parallel Single-Pass Learning"
collection: publications
category: conferences
permalink: /publication/yu2022understanding
excerpt: #''
date: 2022-01-01
venue: '36th Conference on Neural Information Processing Systems (NeurIPS 2022)'
link: 'https://proceedings.neurips.cc/paper_files/paper/2022/hash/080be5eb7e887319ff30c792c2cbc28c-Abstract-Conference.html'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2022/hash/080be5eb7e887319ff30c792c2cbc28c-Abstract-Conference.html'
codeurl: 'https://github.com/Cornell-RelaxML/Hyperdimensional-Computing'
citation: '<strong>Tao Yu*</strong>, Yichi Zhang*, Zhiru Zhang, Christopher De Sa.'
---

Hyperdimensional computing (HDC) is an emerging learning paradigm that computes with high dimensional binary vectors. There is an active line of research on HDC in the community of emerging hardware because of its energy efficiency and ultra-low latency---but HDC suffers from low model accuracy, with little theoretical understanding of what limits its performance. We propose a new theoretical analysis of the limits of HDC via a consideration of what similarity matrices can be expressed by binary vectors, and we show how the limits of HDC can be approached using random Fourier features (RFF). We extend our analysis to the more general class of vector symbolic architectures (VSA), which compute with high-dimensional vectors (hypervectors) that are not necessarily binary. We propose a new class of VSAs, finite group VSAs, which surpass the limits of HDC. Using representation theory, we characterize which similarity matrices can be expressed by finite group VSA hypervectors, and we show how these VSAs can be constructed. Experimental results show that our RFF method and group VSA can both outperform the state-of-the-art HDC model by up to 7.6% while maintaining hardware efficiency. This work aims to inspire a future interest on HDC in the ML community and connect to the hardware community.

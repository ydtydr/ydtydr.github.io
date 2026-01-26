---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Welcome to my homepage!

I am a Scientist at AWS Neuron Science team in the [Annapurna Labs](https://amazon.jobs/content/en/teams/amazon-web-services/annapurna-labs), working on the design and support of large-scale pretraining algorithms for AWS Trainium. I received my Ph.D. degree in Computer Science from Cornell University, advised by [Chris De Sa](https://www.cs.cornell.edu/~cdesa/). I'm also grateful to work with [Vitaly Shmatikov](https://www.cs.cornell.edu/~shmat/) on machine learning privacy. Prior to Cornell, I obtained bachelor degree in Mathematics (ZhiYuan Honors) from Shanghai Jiao Tong University, where I am fourtunate to be advised by [John E. Hopcroft](https://www.cs.cornell.edu/jeh/) and [Huan Long](https://basics.sjtu.edu.cn/~longhuan/).

I work on improving the efficiency of machine learning systems to address growing computational demands. My research focuses on:

- **Optimizing training and inference efficiency** through low-precision methods (e.g., FP8, FP4) and post-training quantization
- **Robust and scalable learning**, including training instabilities and predictive scaling behaviors in LLMs
- **Designing data-aware representations** that leverage the inherent geometry of data

Recently, I have been particularly passionate about algorithm–hardware co-design—understanding the limitations and capabilities of both hardware and software, leveraging their strengths, and developing methods that enable efficient and reliable training and inference. My goal is to simplify the development and deployment of foundation models on hardware. My research interests also extend to private and robust machine learning algorithms. 

<!-- [CV](https://ydtydr.github.io/files/tao_resume.pdf) -->

<!-- For my research, I am intrigued by the prospect of integrating data geometry into machine learning and NLP, as it helps capture diverse properties exhibited by data across various tasks. I'm also dedicated to developing efficient algorithmic and library solutions to ensure the robust numerical computation of low-precision ML models. Additionally, my interests extend to LLMs, machine learning privacy and robustness, along with a curiosity for emerging cognitive learning paradigms such as vector symbolic architectures and hyperdimensional computing. -->

<!-- Hyperbolic Deep Learning
======
Hyperbolic Space is particularly interesting and promising in machine learning due to its non-Euclidean properties. For example, volume of a ball in the hyperbolic space increases exponentially w.r.t. the radius (polynomially in Euclidean space). This imitates a tree, where the number of nodes increases exponentially over the depth (with a fixed branch factor).
We propose HyLa, a completely different approach to using hyperbolic space in graph learning: HyLa maps once from a learned hyperbolic-space embedding to Euclidean space via the eigenfunctions of the Laplacian operator in the hyperbolic space. HyLa is inspired by the random Fourier feature methodology, which uses the eigenfunctions of the Laplacian in Euclidan space. HyLa shows significant improvements over (hyperbolic) GCNs on downstream tasks including node classification and text classification.
We also look into a critical issue of using hyperbolic space: the NaN problem. We proposed tiling-based models and multi-component floats models to solve the NaN problem both theoretically and empirically, currently we are working on a Library to use these techniques easily in ML.

Machine Learning Privacy & Security
======
Despite of the great success of Machine learning, there are also some concerns calling for attention, namely, the security and privacy concern. On the one hand, Machine Learning models are vulnerable to imperceptible adversarial perturbations, which alter the model's decision entirely, it's necessary and worthwhile to design robust and secure models for various applications. On the other hand, Machine Learning models also suffer from information leakage, attacks such as membership inference and model inversion are able to infer information of the dataset. Hence, it's important to measure the information leakage and design privacy-preserving models and algorithms. However, both aspects may degrade the model's performace. What's more, it's particularly interesting to ask whether there is a tradeoff between robustness and privacy, we are currently looking at these tradeoffs in detail.

Federated Learning
======
Federated learning is proposed for collaborative Machine Learning without centralized training data. Users will be able to collaboratively learn a shared model while keeping all the data on device. Latest FL approaches use differential privacy or robust aggregation to ensure privacy and integrity of the federated model, however, we show that these approaches will destroy the accuracy of the federated model for many participants. Thus, we propose local adaptation of federated models, our evaluatation of different techniques demonstrate that all participants benefit from local adaptation. -->
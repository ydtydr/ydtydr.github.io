---
title: 'Momentum Approximation in Asynchronous Private Federated Learning'
collection: publications
category: workshops
permalink: /publication/yu2024momentum
excerpt: #''
date: 2024-01-01
venue: 'International Workshop on Federated Foundation Models (FL@FM-NeurIPS 2024 <strong>Oral</strong>)'
link: 'https://arxiv.org/abs/2402.09247'
paperurl: 'https://arxiv.org/abs/2402.09247'
citation: '<strong>Tao Yu</strong>, Congzheng Song, Jianyu Wang, Mona Chitnis.'
---

Asynchronous protocols have been shown to improve the scalability of federated learning (FL) with a massive number of clients. Meanwhile, momentum-based methods can achieve the best model quality in synchronous FL. However, naively applying momentum in asynchronous FL algorithms leads to slower convergence and degraded model performance. It is still unclear how to effective combinie these two techniques together to achieve a win-win. In this paper, we find that asynchrony introduces implicit bias to momentum updates. In order to address this problem, we propose momentum approximation that minimizes the bias by finding an optimal weighted average of all historical model updates. Momentum approximation is compatible with secure aggregation as well as differential privacy, and can be easily integrated in production FL systems with a minor communication and storage cost. We empirically demonstrate that on benchmark FL datasets, momentum approximation can achieve 1.15--4× speed up in convergence compared to naively combining asynchronous FL with momentum.

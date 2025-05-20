---
title: "Simplifying Graph Convolutional Networks"
collection: publications
category: conferences
permalink: /publication/wu2019simplifying
excerpt: #''
date: 2019-01-01
venue: '36th International Conference on Machine Learning (ICML 2019)'
link: 'https://proceedings.mlr.press/v97/wu19e'
paperurl: 'https://proceedings.mlr.press/v97/wu19e'
codeurl: 'https://github.com/Tiiiger/SGC'
citation: 'Felix Wu*, Tianyi Zhang*, Amauri Holanda de Souza Jr.*, Christopher Fifty, <strong>Tao Yu</strong>, Kilian Q. Weinberger.'
---

Graph Convolutional Networks (GCNs) and their variants have experienced significant attention and have become the de facto methods for learning graph representations. GCNs derive inspiration primarily from recent deep learning approaches, and as a result, may inherit unnecessary complexity and redundant computation. In this paper, we reduce this excess complexity through successively removing nonlinearities and collapsing weight matrices between consecutive layers. We theoretically analyze the resulting linear model and show that it corresponds to a fixed low-pass filter followed by a linear classifier. Notably, our experimental evaluation demonstrates that these simplifications do not negatively impact accuracy in many downstream applications. Moreover, the resulting model scales to larger datasets, is naturally interpretable, and yields up to two orders of magnitude speedup over FastGCN.

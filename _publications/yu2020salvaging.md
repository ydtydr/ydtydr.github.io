---
title: "Salvaging Federated Learning by Local Adaptation"
collection: publications
category: manuscripts
permalink: /publication/yu2020salvaging
excerpt: #''
date: 2020-01-01
venue: 'arXiv preprint arXiv:2002.04758'
link: 'https://arxiv.org/abs/2002.04758'
paperurl: 'https://arxiv.org/abs/2002.04758'
codeurl: 'https://github.com/ebagdasa/federated_adaptation'
citation: '<strong>Tao Yu</strong>, Eugene Bagdasaryan, Vitaly Shmatikov.'
---

Federated learning (FL) is a heavily promoted approach for training ML models on sensitive data, e.g., text typed by users on their smartphones. FL is expressly designed for training on data that are unbalanced and non-iid across the participants. To ensure privacy and integrity of the fedeated model, latest FL approaches use differential privacy or robust aggregation.
We look at FL from the \emph{local} viewpoint of an individual participant and ask: (1) do participants have an incentive to participate in FL? (2) how can participants \emph{individually} improve the quality of their local models, without re-designing the FL framework and/or involving other participants?
First, we show that on standard tasks such as next-word prediction, many participants gain no benefit from FL because the federated model is less accurate on their data than the models they can train locally on their own. Second, we show that differential privacy and robust aggregation make this problem worse by further destroying the accuracy of the federated model for many participants.
Then, we evaluate three techniques for local adaptation of federated models: fine-tuning, multi-task learning, and knowledge distillation. We analyze where each is applicable and demonstrate that all participants benefit from local adaptation. Participants whose local models are poor obtain big accuracy improvements over conventional FL. Participants whose local models are better than the federated model and who have no incentive to participate in FL today improve less, but sufficiently to make the adapted federated model better than their local models.

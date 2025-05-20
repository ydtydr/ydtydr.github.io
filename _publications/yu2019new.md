---
title: "A New Defense Against Adversarial Images: Turning a Weakness into a Strength"
collection: publications
category: conferences
permalink: /publication/yu2019new
excerpt: #''
date: 2019-01-02
venue: '33rd Conference on Neural Information Processing Systems (NeurIPS 2019)'
link: 'https://proceedings.neurips.cc/paper_files/paper/2019/hash/cbb6a3b884f4f88b3a8e3d44c636cbd8-Abstract.html'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2019/hash/cbb6a3b884f4f88b3a8e3d44c636cbd8-Abstract.html'
codeurl: 'https://github.com/s-huu/TurningWeaknessIntoStrength'
citation: '<strong>Tao Yu*</strong>, Shengyuan Hu*, Chuan Guo, Weilun Chao, Kilian Q. Weinberger.'
---

Natural images are virtually surrounded by low-density misclassified regions that can be efficiently discovered by gradient-guided search --- enabling the generation of adversarial images. While many techniques for detecting these attacks have been proposed, they are easily bypassed when the adversary has full knowledge of the detection mechanism and adapts the attack strategy accordingly. In this paper, we adopt a novel perspective and regard the omnipresence of adversarial perturbations as a strength rather than a weakness. We postulate that if an image has been tampered with, these adversarial directions either become harder to find with gradient methods or have substantially higher density than for natural images. We develop a practical test for this signature characteristic to successfully detect adversarial attacks, achieving unprecedented accuracy under the white-box setting where the adversary is given full knowledge of our detection mechanism.

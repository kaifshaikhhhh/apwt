---
title: "Implementing Adaptations for Vision AutoRegressive Model"
collection: publications
category: conferences
permalink: /publication/adapt_iars
excerpt: 'We implement (private and non-private) adaptations of Vision AutoRegressive Model, and benchmark them against SOTA adaptation for diffusion models.'
date: 2025-07-17
venue: 'DIG-BUGS: Data in Generative Models Workshop @ ICML 2025'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://openreview.net/forum?id=YsTotIsCys'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

Vision AutoRegressive model (VAR) was recently introduced as an alternative to Diffusion Models (DMs) in image generation domain. In this work we focus on its adaptations, which aim to fine-tune pre-trained models to perform specific downstream tasks, like medical data generation. While for DMs there exist many techniques, adaptations for VAR remain underexplored. Similarly, differentially private (DP) adaptations---ones that aim to preserve privacy of the adaptation data---have been extensively studied for DMs, while VAR lacks such solutions. In our work, we implement and benchmark many strategies for VAR, and compare them to state-of-the-art DM adaptation strategies. We observe that VAR outperforms DMs for non-DP adaptations, however, the performance of DP suffers, which necessitates further research in private adaptations for VAR. Code is available at [here](https://github.com/sprintml/finetuning_var_dp).
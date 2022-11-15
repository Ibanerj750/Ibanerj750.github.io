---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Ongoing Work
======
1. Banerjee, I., Honnappa, H., &  Rao, V. A. (2023+). Histogram based optimal estimation for controlled Markov chains
1. Banerjee, I., & Honorio, J. (2023+). Fair Combinatorial Logistic Regression: Sparsistency and Sample complexity.
1. Banerjee, I., & Jaiswal, P. (2023+). A Variational Approach to Thompson Sampling for Offline Bandits

Submitted/Published Work
======
1. Banerjee, I., Honnappa, H., &  Rao, V. A. (2022) Offline Estimation of Controlled Markov Chains: Minimax Nonparametric Estimators and Sample Efficiency [Arxiv](https://arxiv.org/abs/2211.07092)
1. Banerjee, I., & Honorio, J. (2022). Meta Sparse Principle Component Analysis. [Arxiv](https://arxiv.org/abs/2208.08938)
1. Banerjee, I., Rao, V. A., & Honnappa, H. (2021). PAC-Bayes Bounds on Variational Tempered Posteriors for Markov Models. Entropy, 23(3), 313. [Approximate Bayesian Inference, Entropy](https://www.mdpi.com/1099-4300/23/3/313)
1. Banerjee, I., Mullick, S. S., & Das, S. (2018). On Convergence of the Class Membership Estimator in Fuzzy $ k $-Nearest Neighbor Classifier. IEEE Transactions on Fuzzy Systems, 27(6), 1226-1236. [Transactions on Fuzzy Sets and Systems](https://ieeexplore.ieee.org/abstract/document/8481381)


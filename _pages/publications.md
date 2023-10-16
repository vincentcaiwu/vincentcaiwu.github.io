---
layout: archive
title: "Ongoing projects"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
* Adding and subtractin Merton: A new approach for the optimal portfolio problem
  - Proposed a diffusion-operator-integral-expansion-based method to solve optimal investment and consumption problems under several models.
  - Programmed for numerical experiments for the application of the proposed method to the optimal investment problem under several stochastic models, including the CEV, Heston, 4/2, SABR model, and optimal investment-consumption problem under the Heston model. 

* Offline simulation of portfolio default risk under stochastic volatility models
  - Replicated numerical tests implemented in [Jiang et al. (2019)](https://pubsonline.informs.org/doi/10.1287/ijoc.2019.0892) to verify their proposed method to measure the portfolio default risk.
  - Combined variance reduction techniques like EMS to the simulation as a modification to the perturbation method.
  - Designed and programmed for additional experiments for underlying assets modeled by the 3/2 model, α-hypergeometric model and portfolio including path-dependent products like arithmetic Asian options and lookback options to illustrate the accuracy and efficiency of the proposed method.

* Explicit quantile through Fourier cosine expansion and Lagrange inversion
  - Derived an explicit representation of quantile in terms of the specified probability utilizing Fourier cosine expansion and Lagrange inversion theorem.
  - Derived an alternative representation of quantile by a direct expansion of the cumulative density function.
  - Implemented a numerical test of normal distribution.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

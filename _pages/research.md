---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

[One-Shot Learning of Stochastic Differential Equations with Computational Graph Completion](https://www.researchgate.net/publication/358263232_One-Shot_Learning_of_Stochastic_Differential_Equations_with_Computational_Graph_Completion) (Preprint)

[Learning dynamical systems from data: a simple cross-validation perspective, part II: nonparametric kernel flows](https://www.researchgate.net/publication/356818178_Learning_dynamical_systems_from_data_a_simple_cross-validation_perspective_part_II_nonparametric_kernel_flows) (Preprint)

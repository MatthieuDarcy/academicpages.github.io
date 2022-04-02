---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Papers
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Talks 

My talk on the [applications of kernels flows to regression](https://www.youtube.com/watch?v=ZndevdR4omw) (Symposium on Machine Learning and Dynamical systems at the Fields institute)





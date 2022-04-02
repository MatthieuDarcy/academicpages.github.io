---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Papers

You can also find my articles on [my Google Scholar profile](https://scholar.google.com/citations?user=_KSmKigAAAAJ&hl=en)


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Talks 
{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}





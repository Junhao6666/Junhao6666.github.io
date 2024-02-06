---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

[Advancing Crowd Forecasting with Graphs across Microscopic Trajectory to Macroscopic Dynamics accepted by information fusion.](https://www.sciencedirect.com/science/article/pii/S1566253524000538)



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

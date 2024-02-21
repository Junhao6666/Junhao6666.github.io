---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## First author

## Co-first author
Xie, C. Z. T., Xu, J., Zhu, B., Tang, T. Q., Lo, S., Zhang, B., & Tian, Y. (2024). Advancing crowd forecasting with graphs across microscopic trajectory to macroscopic dynamics. Information Fusion, 102275.[PDF](https://www.sciencedirect.com/science/article/pii/S1566253524000538)

## Corresponding author

## Others

## Under review

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

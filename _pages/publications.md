---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Publications in peer-reviewed scientific journals
------

1. **Adam, T.**, Mayr, A., and Kneib, T. (2021).\\
Gradient boosting in Markov-switching generalized additive models for location, scale, and shape.\\
*Econometrics and Statistics, Part B: Statistics*, accepted.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

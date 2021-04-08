---
permalink: /portfolio/
title:
excerpt:
author_profile: true
---

<img src='/images/StA3.png' width='895'>

Projects
=======

{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}


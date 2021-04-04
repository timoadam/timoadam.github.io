---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Publications in peer-reviewed scientific journals
------

1. **Adam, T.**, Mayr, A., and Kneib, T. (2021):\\
Gradient boosting in Markov-switching generalized additive models for location, scale, and shape.\\
*Econometrics and Statistics, Part B: Statistics*, accepted.

2. Lennox, R.J., Westrelin, S., Souza, A.T., Šmejkal, M., Říha, M., Prchalová, M., Nathan, R., Monk, C., Koeck, B., Killen, S., Jarić, I., Gjelland, K., Hollins, J., Hellstrom, G., Hansen, H., Cooke, S.J., Boukal, D., Brooks, J.L., Brodin, T., Baktoft, H., **Adam, T.**, and Arlinghaus R. (2021):\\
A role for lakes in revealing the nature of animal movement using high dimensional telemetry systems.\\
*Movement Ecology*, accepted.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

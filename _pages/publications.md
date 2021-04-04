---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Publications in peer-reviewed scientific journals
------

1. **Adam, T.**, Mayr, A., and Kneib, T. (2021):\\
Gradient Boosting in Markov-switching Generalized Additive Models for Location, Scale, and Shape.\\
*Econometrics and Statistics, Part B: Statistics*, accepted.

2. Lennox, R.J., Westrelin, S., Souza, A.T., Šmejkal, M., Říha, M., Prchalová, M., Nathan, R., Monk, C., Koeck, B., Killen, S., Jarić, I., Gjelland, K., Hollins, J., Hellstrom, G., Hansen, H., Cooke, S.J., Boukal, D., Brooks, J.L., Brodin, T., Baktoft, H., **Adam, T.**, and Arlinghaus R. (2021):\\
A Role for Lakes in Revealing the Nature of Animal Movement Using High-dimensional Telemetry Systems.\\
*Movement Ecology*, accepted.

3. **Adam, T.**, Griffiths, C.A., Leos-Barajas, V., Meese, E.N., Lowe, C.G., Blackwell, P.G., Righton, D., and Langrock, R. (2019):\\
Joint Modelling of Multi-scale Animal Movement Data Using Hierarchical Hidden Markov Models.\\
*Methods in Ecology and Evolution*, 10(9), 1536-1550.



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

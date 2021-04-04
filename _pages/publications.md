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
*Methods in Ecology and Evolution*, **10**(9), 1536-1550.

4. **Adam, T.**, Langrock, R., and Weiß, C.H. (2019):\\
Penalized Estimation of Flexible Hidden Markov Models for Time Series of Counts.\\
*METRON*, **77**(2), 87-104.

5.	Langrock, R., **Adam, T.**, Leos-Barajas, V., Mews, S., Miller, D.L., and Papastamatiou, Y.P. (2018):\\
Spline-based Non-parametric Inference in General State-switching Models.\\
*Statistica Neerlandica*, **72**(3), 179-200.

6.	Leos-Barajas, V., Gangloff, E.J., **Adam, T.**, Langrock, R., van Beest, F.M., Nabe-Nielsen, J., and Morales, J.M. (2017):\\
Multi-scale Modeling of Animal Movement and General Behavior Data Using Hidden Markov Models with Hierarchical Structures.\\
*Journal of Agricultural, Biological, and Environmental Statistics*, **22**(3), 232-248.

Preprints
------

7. Nagel, R., Mews, S., **Adam, T.**, Stainfield, C., Fox-Clarke, C., Toscani, C., Langrock, R., Forcada, J., and Hofmann, J.I. (2021):\\
Movement Patterns and Activity Levels are Shaped by The Neonatal Environment in Antarctic Fur Seal Pups.\\
*bioarXiv*.

8. Pohle, J., **Adam, T.**, and Beumer, L.T. (2021):\\
Flexible Estimation of the State Dwell-time Distribution in Hidden Semi-Markov Models.\\
*arXiv*.

9. Oelschläger, L. and **Adam, T.** (2020):\\
Detecting Bearish and Bullish Markets in Financial Time Series Data Using Hierarchical Hidden Markov Models.\\
*arXiv*.

Publications in conference proceedings
------

10. **Adam, T.** and Oelschläger, L. (2020):\\
Hidden Markov models for multi-scale time series: an application to stock market data.\\
*Proceedings of the 35th International Workshop on Statistical Modelling*, **1**.

11.	Pohle, J., **Adam, T.**, Beumer, L.T., and Langrock, R. (2020):\\
Flexible Estimation of the State Dwell-time Distribution in Hidden Semi-Markov Models.\\
*Proceedings of the 35th International Workshop on Statistical Modelling*, **1**.

12.	**Adam, T.**, Langrock, R., and Kneib, T. (2019):\\
Model-based Clustering of Time Series Data: a Flexible Approach Using Non-parametric State-switching Quantile Regression Models.\\
*Book of Short Papers of the 12th Scientific Meeting on Classification and Data Analysis*, 19-22.

13.	**Adam, T.**, Langrock, R., and Weiß, C.H. (2019):\\
Non-parametric Inference in Hidden Markov Models for Time Series of Counts.\\
*Proceedings of the 34th International Workshop on Statistical Modelling*, **1**, 135-140.

14.	**Adam, T.**, Mayr, A., Kneib, T., and Langrock, R. (2018):\\
Statistical Boosting for Markov-switching Distributional Regression Models.\\
*Proceedings of the 33rd International Workshop on Statistical Modelling*, **1**, 30-35.

15.	**Adam, T.**, Leos-Barajas, V., Langrock, R., and van Beest, F.M. (2017):\\
Using Hierarchical Hidden Markov Models for Joint Inference at Multiple Temporal Scales.\\
*Proceedings of the 32nd Interna-tional Workshop on Statistical Modelling*, **2**, 181-184.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
fontsize: 8pt
---

Publications in peer-reviewed scientific journals
------

- **Adam, T.**, Mayr, A., and Kneib, T. (2021):\\
Gradient boosting in Markov-switching generalized additive models for location, scale, and shape.\\
*Econometrics and Statistics, Part B: Statistics*, accepted.

- Lennox, R.J., Westrelin, S., Souza, A.T., Šmejkal, M., Říha, M., Prchalová, M., Nathan, R., Monk, C., Koeck, B., Killen, S., Jarić, I., Gjelland, K., Hollins, J., Hellstrom, G., Hansen, H., Cooke, S.J., Boukal, D., Brooks, J.L., Brodin, T., Baktoft, H., **Adam, T.**, and Arlinghaus R. (2021):\\
A role for lakes in revealing the nature of animal movement using high-dimensional telemetry systems.\\
*Movement Ecology*, accepted.

- **Adam, T.**, Griffiths, C.A., Leos-Barajas, V., Meese, E.N., Lowe, C.G., Blackwell, P.G., Righton, D., and Langrock, R. (2019):\\
Joint modelling of multi-scale animal movement data using hierarchical hidden Markov models.\\
*Methods in Ecology and Evolution*, **10**(9), 1536-1550.

- **Adam, T.**, Langrock, R., and Weiß, C.H. (2019):\\
Penalized estimation of flexible hidden Markov models for time series of counts.\\
*METRON*, **77**(2), 87-104.

-	Langrock, R., **Adam, T.**, Leos-Barajas, V., Mews, S., Miller, D.L., and Papastamatiou, Y.P. (2018):\\
Spline-based non-parametric inference in general state-switching models.\\
*Statistica Neerlandica*, **72**(3), 179-200.

-	Leos-Barajas, V., Gangloff, E.J., **Adam, T.**, Langrock, R., van Beest, F.M., Nabe-Nielsen, J., and Morales, J.M. (2017):\\
Multi-scale modeling of animal movement and general behavior data using hidden Markov models with hierarchical structures.\\
*Journal of Agricultural, Biological, and Environmental Statistics*, **22**(3), 232-248.

Preprint publications
------

- Nagel, R., Mews, S., **Adam, T.**, Stainfield, C., Fox-Clarke, C., Toscani, C., Langrock, R., Forcada, J., and Hofmann, J.I. (2021):\\
Movement patterns and activity levels are shaped by the neonatal environment in Antarctic fur seal pups.\\
*bioarXiv*.

- Pohle, J., **Adam, T.**, and Beumer, L.T. (2021):\\
Flexible estimation of the state dwell-time distribution in hidden semi-Markov models.\\
*arXiv*.

- Oelschläger, L. and **Adam, T.** (2020):\\
Detecting bearish and bullish markets in financial time series data using hierarchical hidden Markov models.\\
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

Software
------

16.	Oelschläger, L. and **Adam, T.** (2021):\\
fHMM: Fitting Hidden Markov Models to Financial Time Series.\\
*R package*, 0.2.0, CRAN.

17. **Adam, T.** (2019):\\
countHMM: Penalized Estimation of Flexible Hidden Markov Models for Time Series of Counts.\\
*R package*, 0.1.0, CRAN.




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

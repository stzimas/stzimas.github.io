---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

`{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}`

In Journals
-
* Charis Papadopoulos and Spyridon Tzimas. [Subset feedback vertex set on graphs of bounded independent set size.](https://doi.org/10.1016/j.tcs.2020.01.029) _Theoretical Computer Science_, 814:177–188, 2020.
* Charis Papadopoulos and Spyridon Tzimas. [Polynomial-time algorithms for the subset feedback vertex set problem on interval graphs and permutation graphs.](https://doi.org/10.1016/j.dam.2018.11.017) _Discrete Applied Mathematics_, 258:204–221, 2019.

In Conference Proceedings
-
* Charis Papadopoulos and Spyridon Tzimas. [Subset Feedback Vertex Set on Graphs of Bounded Independent Set Size.](https://doi.org/10.4230/LIPIcs.IPEC.2018.20) 13th International Symposium on Parameterized and Exact  Computation (**IPEC 2018**). _Leibniz International Proceedings in Informatics (LIPIcs)_, 115:20:1--20:14, 2019.
* Charis Papadopoulos and Spyridon Tzimas. [Polynomial-Time Algorithms for the Subset Feedback Vertex Set Problem on Interval Graphs and Permutation Graphs.](https://doi.org/10.1007/978-3-662-55751-8_30) 21st International Symposium on Fundamentals of Computation Theory (**FCT 2017**). _Lecture Notes in Computer Science (LNCS)_, 10472:381--394, 2017.

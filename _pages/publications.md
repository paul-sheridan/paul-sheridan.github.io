---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**Sheridan, P.**, Onsjö, M. (2023). "The hypergeometric test performs comparably to a common TF-IDF variant on standard information retrieval tasks." <i>Multimedia Tools and Applications (**under review**). </i> Preprint available at <a href="https://arxiv.org/abs/2002.11844" target="_blank" rel="noopener"> arXiv </a>.


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

**Shaohua Guan**, Zhichao Zhang, Hualin Shi **_Critical phenomenon in the flux space of genome-scale metabolic networks_**, 2019, Prepare a manuscript.

**Shaohua Guan**, Liufang Xu, Qing Zhang, Hualin Shi **_Trade-offs between efficiency and cost in two-component robust regulatory system_**, 2019, Submitted to PRE.


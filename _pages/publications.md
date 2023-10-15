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

- **[ASPLOS'24] Proteus: A High-Throughput Inference-Serving System with Accuracy Scaling.** [[PDF](http://guanh01.github.io/files/2024proteus.pdf)][[Code](https://github.com/UMass-LIDS/Proteus)]
<br> Sohaib Ahmad, Hui Guan, Brain D. Friedman, Thomas Williams, Ramesh K. Sitaraman, Thomas Woo.
<br> The 2024 ACM Conference on Architectural Support for Programming Languages and Operating Systems, April 27-May 1, 2024.

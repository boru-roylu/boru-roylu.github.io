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

<b>[Order-Preserving Abstractive Summarization for Spoken Content Based on Connectionist Temporal Classification](https://arxiv.org/abs/1709.05475)</b> <br> B. R. Lu, F. Shyu, Y.-N. Chen, H.-Y. Lee, L.-S. Lee. <i>INTERSPEECH 2017</i>. [[PDF]](https://arxiv.org/abs/1709.05475)

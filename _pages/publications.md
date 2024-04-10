---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

See my publication list also on <u><a href="https://scholar.google.com/citations?user=mo8ddGYAAAAJ">my Google Scholar profile</a>.</u>

## Latest pre-prints

* Luis S. Luevano, Leonardo Chang, Miguel González-Mendoza, Yoanna Martínez-Díaz, Heydi Méndez-Vázquez, et al.. BinaryFaceNet: A Binarized Approach for Real-Time Very Low Resolution Face Recognition in Video Surveillance Scenarios. 2024. ⟨hal-04393666⟩
* Luis S. Luevano, Davide Frey. Analyzing Trusted Execution Environments: Comparing Commercial Implementations and Diverse Applications. 2024. ⟨hal-04393667⟩

## Peer-reviewed publications

{% include base_path %}

{% assign current_year = '0' %}
{% for post in site.publications reversed %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if current_year != year %} 
## {{ year }}
    {% assign current_year = year %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}

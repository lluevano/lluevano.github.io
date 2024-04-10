---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

See my publication list also on <u><a href="https://scholar.google.com/citations?user=mo8ddGYAAAAJ">my Google Scholar profile</a>.</u>

<details> 
<summary> <h2>Latest pre-prints</h2> </summary>

*Testing*

</details> 

## Peer-reviewed publications

{% include base_path %}

{% assign current_year = '0' %}
{% for post in site.publications reversed %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if current_year != year %} 
    <h3> {{ year }} </h3>
    {% assign current_year = year %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}

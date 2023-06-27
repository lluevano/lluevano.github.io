---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

See my publication list also on <u><a href="https://scholar.google.com/citations?user=mo8ddGYAAAAJ">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

See my publication list also on <u><a href="https://scholar.google.com/citations?user=mo8ddGYAAAAJ">my Google Scholar profile</a>.</u>

## Working papers

* Luis S. Luevano, Leonardo Chang, Miguel González-Mendoza, Yoanna Martínez-Díaz, Heydi Méndez-Vázquez, et al.. BinaryFaceNet: A Binarized Approach for Real-Time Very Low Resolution Face Recognition in Video Surveillance Scenarios. 2024. ⟨hal-04393666⟩
* Luis S. Luevano, Davide Frey. Analyzing Trusted Execution Environments: Comparing Commercial Implementations and Diverse Applications. 2024. ⟨hal-04393667⟩
* Luis S. Luevano, Davide Frey, Marc Sel, Dave Singelee. SOTERIA D5.4 HARDWARE-BASED PRIVACY. 2024. ⟨hal-04393670⟩

<details>
<summary><strong>Peer-reviewed extended abstracts</strong></summary>

<ul>
<li>Luis S. Luevano, Miguel González-Mendoza, Yoanna Martínez-Díaz, Heydi Méndez-Vázquez. Exploring the Potential for Real-Time Vision Transformer-Level Precision on Face Recognition Scenarios through Binarization on Embedded Systems.  ICCVW 2023 - IEEE/CVF International Conference on Computer Vision Workshops, Oct 2023, Paris, France. 2023. (hal-04393662)
<ul>
<li><a href="/files/ICCV23_LXAI_ExtendedAbstract.pdf">Extended abstract</a></li>
<li><a href="/files/LUEVANO-GARCIA-Luis-Santiago-WIDE-ICCVW2023-Poster-LXAI.pdf">Poster</a></li>
</ul>
</li>
</ul>

</details>

## Peer-reviewed publications

{% include base_path %}

{% assign current_year = '0' %}
{% for post in site.publications reversed %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if current_year != year %} 
### {{ year }}
    {% assign current_year = year %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}

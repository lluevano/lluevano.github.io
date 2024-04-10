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
* Luis S. Luevano, Martínez-Díaz Yoanna, Méndez-Vázquez Heydi, González-Mendoza Miguel, Davide Frey. SwiftFaceFormer: An Efficient and Lightweight Hybrid Architecture for Accurate Face Recognition Applications. 2024. ⟨hal-04393675⟩
* Luis S. Luevano, Davide Frey, Marc Sel, Dave Singelee. SOTERIA D5.4 HARDWARE-BASED PRIVACY. 2024. ⟨hal-04393670⟩

<details>
<summary>

<h2>Peer-reviewed extended abstracts</h2>

</summary>

<ul>
<li>Luis S. Luevano, Miguel González-Mendoza, Yoanna Martínez-Díaz, Heydi Méndez-Vázquez. Exploring the Potential for Real-Time Vision Transformer-Level Precision on Face Recognition Scenarios through Binarization on Embedded Systems. CVPRW 2023 - IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops, Jun 2023, Vancouver, Canada. 2023. ffhal-04393662f</li>
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

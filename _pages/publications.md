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

## Extended abstracts

* Luis S. Luevano, Davide Frey. "Towards Large-Scale Privacy-Preserving Decentralized Machine Learning-Based Computer Vision Systems". Submitted to the LatinX in AI Workshop at CVPR 2024 (not accepted). 2024.

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

## Peer-reviewed extended abstracts

* Luis S. Luevano, Miguel González-Mendoza, Yoanna Martínez-Díaz, Heydi Méndez-Vázquez. "Exploring the Potential for Real-Time Vision Transformer-Level Precision on Face Recognition Scenarios through Binarization on Embedded Systems". LatinX in AI Workshop at ICCV 2023 - IEEE/CVF International Conference on Computer Vision Workshops, Paris, France, October 2023. [Extended abstract](/files/ICCV23_LXAI_ExtendedAbstract.pdf), [Poster](/files/LUEVANO-GARCIA-Luis-Santiago-WIDE-ICCVW2023-Poster-LXAI.pdf), [hal-04393662](https://inria.hal.science/hal-04393662)

## Project deliverables

* Luis S. Luevano, Davide Frey, Marc Sel, Dave Singelee. "SOTERIA D5.4 Hardware-Based Privacy". EU H2020 SOTERIA project, 2024. [Official document](https://ec.europa.eu/research/participants/documents/downloadPublic?documentIds=080166e50221d995&appId=PPGMS), [hal-04393670](https://inria.hal.science/hal-04393670)

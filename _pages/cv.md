---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
<table class="no_border">
    <tbody>
      <tr>
            <td><a href="https://tec.mx"><img src="/images/tec_logo.png"></a></td>
            <td><div>Tecnológico de Monterrey</div><div>State of Mexico, Mexico</div></td>
            <td>Ph.D. in Computer Science</td>
            <td>Jan 2019 - Dec 2022</td>
        </tr>
        <tr>
            <td><a href="https://www.stevens.edu/"><img src="/images/stevens_logo.png"></a></td>
            <td><div>Stevens Institute of Technology</div><div>New Jersey, USA</div></td>
            <td>M.Sc. in Computer Science</td>
            <td>Aug. 2016 - May 2018</td>
        </tr>
        <tr>
            <td><a href="https://tec.mx"><img src="/images/tec_logo.png"></a></td>
            <td><div>Tecnológico de Monterrey</div><div>State of Mexico, Mexico</div></td>
            <td>B.Sc. Computer Science and Technology</td>
            <td>Aug 2011 - Dec 2015</td>
        </tr>
    </tbody>
</table>

<style>
  .no_border, .no_border tr, .no_border td{
    border: none;
    text-align:center;
  }
  .no_border img{
    width: 70%;
    height:auto;
  }
</style>

Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Currently signed in to 43 different slack teams

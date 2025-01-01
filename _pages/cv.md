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
* B.S., University of Science and Technology of China, Jun. 2025 (expected)
  *  Major: Statistics
  *  GPA: 4.00/4.3 (weighted average: 91.8/100)
  *  Ranking: 2/102

Skills
======
* Programming: Python, R, C
* Typesetting: LaTeX, Markdown

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Honors and Awards
======
* Outstanding Student Scholarship (2022, 2023, and 2024)

Contact
======
* Email: tang211061@mail.ustc.edu.cn
* CN Tel: (+86)18956221183
* US Tel: (+1)7345968646

---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Computer Science and Engineering**, _University of Notre Dame_, 2023 (expected)
* **M.S. in Data Science**, _New York University_, 2017
* **B.S. in Applied Mathematics**, _University of California - Loa Angeles_, 2014

---
  
Teaching
======
  <ul>{% for post in site.teaching reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
---

Publications
======
  <ul>{% for post in site.publications reversed%}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

---

Honors & Awards
======
**Outstanding Graduate Student Teaching Award**, _University of Notre Dame_, 2020

**Student Travel Award**, _IEEE BigData_, 2019

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
* Ph.D. in Your Field, Your University, YYYY-present
* M.S. in Your Field, Your University, YYYY
* B.S. in Your Field, Your University, YYYY

Research Experience
======
* Research Assistant, Your Lab or Group, YYYY-present
  * Replace with a short description of your research responsibilities and methods.
  * Replace with a short description of outputs, collaborations, or systems built.

Skills
======
* Research method or technical skill 1
* Research method or technical skill 2
* Programming, data analysis, or writing skill

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Selected Projects
======
  <ul>{% for post in site.portfolio %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Awards and Service
======
* Award or fellowship, YYYY
* Service role, committee, or reviewing activity, YYYY

PDF CV
======
Upload your CV PDF to `files/cv.pdf`, then link it here: [Download CV](/files/cv.pdf).

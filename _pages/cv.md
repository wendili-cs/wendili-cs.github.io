---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Experience
======
* Software Engineer, Epic, 2023.07-present
* Software Engineer Intern, TikTok, 2022.06-2022.09
* Machine Learning Researcher, Microsoft Research, 2020.04-2021.07

Education
======
* M.S. in Computer Science, University of Wisconsin-Madison, 2021.09-2023.05
* B.E. in Computer Science and Technology, South China University of Technology, 2016.09-2020.07
* Exchange Program for Fall 2019, University of California, Berkeley, 2019.08-2020.01
  
Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Projects
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

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
* Ph.D in Political Science, Vanderbilt University, 2019 
* M.A., McGill University, 2013
* B.A., McGill University, 2010

Work experience
======
* Current: Director of Data Science
  * Program on Opinion Research and Election Studies
  * University of Pennsylvania

* Current: Senior Elections Analyst
  * NBC News Decition Desk

* 2019-202: Postdoctoral Research Fellow
  * Washington University in St. Louis
  

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

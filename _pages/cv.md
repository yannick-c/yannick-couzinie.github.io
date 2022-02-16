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
* Ph.D in Mathematics, Roma Tre University, 2022 (expected)
   * Thesis: _The multidimensional East model: a multicolour model and a front
   evolution problem_ (under review)
* Elite-M.Sc. in Theoretical and Mathematical Physics, Ludwig Maximilian University of Munich, 2018
   * Thesis: [_Sublinearly reinforced Pólya urns on graphs of bounded degree_]({{base_path}}/theses/master-thesis)
* B.Sc. in Physics, University of Hamburg, 2016
   * Thesis: [_Multi-channel Kondo effect in finite lattices_]({{base_path}}/theses/bachelor-thesis)

Work experience
======
* 02/2017 - 10/2018: Research software engineer
  * Cognostics AG, Pullach, Germany
  * Develop and implement machine learning and regular algorithms in Python.
  * Implement and maintain the [pep8 coding convention](https://pep8.org/) in the repositories.
  * Keep track of issues and check commits of collaborators on same project.

Skills
======
* Languages
  * German (native)
  * French (native)
  * English (fluent)
  * Japanese (fluent)
  * Italian (fluent)
  * Chinese (intermediate)
* Programming
  * C (OS-programming, graphviz, autoconfig, doxygen)
  * Python (numpy, multiprocessing, pandas, tensorflow)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
{% assign tsize = site.talks | size %}
{% if tsize != 0 %}
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
{% endif %}
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Extracurricular Activities and Achievements
======
* 04/2018 - 10/2018 Member of local board in German green party
* 04/2017 - 09/2017 Scholarship holder of the Ebner Stiftung
* 05/2016 2nd place, Japanese speech contest
   * Annual Germany wide speech contest held by the Japanese Embassy in Germany

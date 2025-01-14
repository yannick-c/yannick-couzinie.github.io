---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Work experience
======
* 10/2022 - present: Postdoctoral Researcher
  * Tokyo Institute of Techonology (~02/2024), University of Tokyo (03/2024~)
    and Quemix Inc., Tokyo, Japan
  * Research on applications for quantum annealing and gate based quantum
  computation
  * Perform simulations to evaluate performance of algorithms

* 02/2017 - 10/2018: Research software engineer
  * Cognostics AG, Pullach, Germany
  * Develop and implement machine learning and regular algorithms in Python.
  * Implement and maintain the [pep8 coding convention](https://pep8.org/) in the repositories.
  * Keep track of issues and check commits of collaborators on same project.

Education
======
* Ph.D in Mathematics, Roma Tre University, 2022
   * Thesis: [_The multidimensional East model: a multicolour model and a front
   evolution problem_](/theses/phd-thesis)
* Elite-M.Sc. in Theoretical and Mathematical Physics, Ludwig Maximilian University of Munich, 2018
   * Thesis: [_Sublinearly reinforced Pólya urns on graphs of bounded degree_]({{base_path}}/theses/master-thesis)
* B.Sc. in Physics, University of Hamburg, 2016
   * Thesis: [_Multi-channel Kondo effect in finite lattices_]({{base_path}}/theses/bachelor-thesis)


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
  * Python (NumPy, torch, pandas, pep8)
  * C (OS programming, autoconfig, doxygen)
  * Fortran (Modern Fortran paradigms, parallel computation)


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
* 12/2023 Award for encouragement of young researchers of Materials Society of
Japan
* 12/2019 - 12/2021 Ph.D. representative in the Commissione Paritetica Docenti Studenti
* 04/2018 - 10/2018 Member of local board in German green party
* 04/2017 - 09/2017 Scholarship holder of the Ebner Stiftung
* 05/2016 2nd place, Japanese speech contest
   * Annual Germany wide speech contest held by the Japanese Embassy in Germany

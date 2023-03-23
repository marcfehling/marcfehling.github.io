---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

For my detailed cv, see the [pdf version](../files/cv.pdf).

Education
======
* Ph.D in Civil Engineering, University of Wuppertal, Germany, 2020
* M.S. in Physics, Ruhr-University Bochum, Germany, 2015
* B.S. in Physics, Ruhr-University Bochum, Germany, 2013

Work experience
======
* October 2020 - now: Postdoctoral Fellow
  * Colorado State University
  * Duties included: Maintenance of deal.II library, Teaching
  * Supervisor: Prof. Dr. Wolfgang Bangerth

* October 2015 - July 2020: Graduate Assistant
  * Jülich Research Center / University of Wuppertal
  * Duties included: Teaching assistant
  * Supervisor: Prof. Dr. Lukas Arnold
  
Skills
======
* Programming languages
  * Daily use of C++, Python
  * In depth knowledge of Matlab, C, Java
* Libraries & APIs
  * deal.II, MPI, p4est, Boost
* Software
  * FDS, SALOME
* Tools
  * LaTeX, pgfplots, tikz, git, CMake, Unix
* Languages
  * German: Native speaker
  * English: Fluent
  * French: Basic communication skills

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* appointed deal.II principal developer since March 2021

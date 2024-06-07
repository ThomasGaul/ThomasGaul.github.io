---
layout: archive
title: "Shortened CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Cognitive Science, Indiana University Bloomington, 2025

Honors and Awards
======
* June 2024: **Murray Austin Goldstone Scholarship**, *Indiana University Cognitive Science*.
* April 2024: **Outstanding Contribution Award**, *Indiana University Cognitive Science*.
* April 2023: **Robert J. Glushko Award for Outstanding Research in Cognitive Science**, *Indiana University Cognitive Science*.
 
Experience
======
* Fall 2023 - Spring 2025: *Organizer*
    * Midwest Undergraduate Cognitive Science Conference
* Spring 2024 - Spring 2025: *Treasurer*
    * Students of Cognitive Science

Skills
======
* Programming Languages: C++, Python, Wolfram Language, Java, Bash
* Software: Linux, Mathematica, LaTeX, Inkscape, Adobe Illustrator

Recent Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

---
layout: archive
title: "Cirriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

See my full CV [here](http://ThomasGaul.github.io/files/Gaul-CV.pdf).

## Education
* B.S. in Cognitive Science, Indiana University Bloomington, 2025.

## Honors and Awards
<!--* September 2024: **Murray Austin Goldstone Scholarship for Undergraduate Research**, *Indiana University Cognitive Science*.-->
* April 2024: **Outstanding Contribution Award**, *Indiana University Cognitive Science*.
* April 2023: **Robert J. Glushko Award for Outstanding Research in Cognitive Science**, *Indiana University Cognitive Science*.

## Experience
* Fall 2023 - Spring 2025: *Organizer*. Midwest Undergraduate Cognitive Science Conference.
* Spring 2024 - Spring 2025: *Treasurer*. Students of Cognitive Science.

## Skills
* Programming Languages: Rust, C++, Wolfram Language, Python, Java, Bash
* Software: Linux, Mathematica, LaTeX, Inkscape, Git, Visual Studio Code, Vim

## Publications
{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
{% endfor %}

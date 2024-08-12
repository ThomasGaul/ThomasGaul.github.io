---
layout: archive
title: "Autopoiesis and Cognition in RealLife Euclidean Automata"
excerpt: "Developing a formal theory of biological organization in a continuous-space, discrete-time univese.<br/><br/><img src='/images/RealLife-Project.png' style='width: 500px'>"
collection: portfolio
---

This project currently aims to extend the definitions of autopoiesis in the Game of Life (GoL) to Larger than Life (LtL), in order to take a limit as LtL rules approach an infinite neighborhood size (RealLife). Once we have definitions for RealLife, we can analyse the structure of *dependency manifolds* (autopoietic networks) and *interaction manifolds* (maps of an individual's responses to perturbations). This requires the development of mathematical tools to analyse autopoiesis in continuous space, thus providing future investigations into more realistic systems with rigorous tools and theoretical insights.

With this, many further questions can be pursued: the conditions for adaptivity, the relation between operational and physical boundaries, structural coupling, the origins of autopoietic systems, how the viability constraint relates to autopoiesis, among many others.

## Relevant Publications
{% for post in site.publications reversed %}
    {% if post.project and post.project == 'RealLife' %}
       {% include archive-single-cv.html %}
    {% endif %}
{% endfor %}

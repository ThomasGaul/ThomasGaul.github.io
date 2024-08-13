---
layout: archive
title: "Autopoiesis and Cognition in RealLife Euclidean Automata"
excerpt: "Developing a formal theory of biological organization in a continuous-space, discrete-time univese.<br/><br/><img src='/images/RealLife-Project.png' style='width: 500px'>"
collection: portfolio
---

This project currently aims to extend the definitions of autopoiesis in the Game of Life (GoL) (Beer, 2020) to Larger than Life (LtL) (Evans, 2001, 2003), in order to take a limit as LtL rules approach an infinite neighborhood size (RealLife) (Pivato, 2007). Once we have definitions for RealLife, we can analyse the structure of *dependency manifolds* (autopoietic networks) and *interaction manifolds* (maps of an individual's responses to perturbations). This requires the development of mathematical tools to analyse autopoiesis in continuous space, thus providing future investigations into more realistic systems with greater rigour and theoretical insights.

The first steps for this project are in developing a formal theory of autopoiesis in LtL, supported by computational results from scaling persistent structures. For instance, for a *bug* in LtL (generalising the glider from GoL), we would like to be able to predict the structure of its autopoietic network without having to extract it independently at each neighborhood size as we scale the bug with the CA rule. The hope is, then, that such a formal theory would allow us to take a limit as the neighbourhood approaches infinity.

Moreover, having a formal definition for autopoietic networks should permit the derivation of a cognitive description of an entity, as has been done for gliders in GoL (Beer et al., 2024; the code for extracting the network and deriving an interaction graph from it is available in <a href="https://github.com/ThomasGaul/glider-dependency-graph">this Github repository</a>).

RealLife also provides an opportunity to develop a formalism for a spatial theoretical chemistry. One of the main failures of most theoretical-chemical approaches to autopoiesis is the lack of spatiality and heterogeneity, but these qualities are essential to any reasonable understanding of living systems. Thus RealLife could be used as a toy universe in which to develop a spatial theory of chemistry and compare it to other adapted formalisms.

With this, many further questions can be pursued: the conditions for adaptivity, the relation between operational and physical boundaries, structural coupling, the origins of autopoietic systems, how the viability constraint relates to autopoiesis, among many others.


## Relevant Publications
{% for post in site.publications reversed %}
    {% if post.project and post.project == 'RealLife' %}
       {% include archive-single-cv.html %}
    {% endif %}
{% endfor %}
<hr style="width:40%">
<p style="font-size:smaller">
Beer, R. D. (2020). <a href="https://doi.org/10.1162/isal_a_00245">An integrated perspective on the constitutive and interactive dimensions of autonomy</a>. In J. Bongard, et al. (Eds.) <i>ALIFE 2020: The 2020 Conference on Artificial Life</i>, pages 202-209. MIT Press.
<br /><br />
Evans, K. M. (2001). <a href="https://doi.org/10.46298/dmtcs.2288">Larger than Life: Digitial creatures in a family of two-dimensial cellular automata</a>. <i>Discrete Mathematics and Theoretical Computer Science, AA</i>, 177-192.
<br /><br />
Evans, K. M. (2003). <a href="https://doi.org/10.1016/S0167-2789(03)00155-6">Larger than Life: Threshold-range scaling of Life's coherent structures</a>. <i>Physica D: Nonlinear Phenomena, 183</i>(1-2), 45-67.
<br /><br />
Pivato, M. (2007). <a href="https://doi.org/10.1016/j.tcs.2006.11.019">RealLife: The continuum limit of Larger than Life cellular automata</a>. <i>Theoretical Computer Science, 372</i>(1), 46-68. Elsevier.
</p>

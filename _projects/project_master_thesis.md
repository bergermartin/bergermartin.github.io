---
layout: page
title: Master's Thesis
description: Using TDA to analyze microscopic images.
img: assets/img/graph.png
redirect: 
importance: 5
category: work
related_publications: FengerEriksen2020, 2023fibrin
---

[Master's Thesis - An Application of Topological Data Analysis to Fibrin Networks]({{ site.url }}/assets/pdf/intro_tda.pdf)

Topological data analysis (TDA) combines statistical inference methods with algebraic topology, allowing to identity the geometric structure within a dataset.

For my master's thesis I developed a methodology to analyze microscopic images of fibrin networks using TDA. 

Fibrin is a protein which is created from fibrinogen and is involved in blood clotting. Thus, it is of high interest how different volume replacements effect the natural fibrin net structure.

My thesis provides an introduction into the basics of algebraic topology, in particular simplicial complexes. We then discuss persistent homology, the building block of topological data analysis and it's application to grayscale images.

For a shorter introduction to the field of topological data analysis, check my [TDA lecture notes]({% link _projects/project_tda_notes.md %}).


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fibrin.png" title="Fibrin Network" class="img-fluid rounded z-depth-1" width="350" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fibrin_diag.png" title="Persistence Diagram" class="img-fluid rounded z-depth-1" width="300" %}
    </div>
</div>

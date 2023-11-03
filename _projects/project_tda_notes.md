---
layout: page
title: TDA
description: A short introduction to topological data analysis for non-mathematicians.
img: assets/img/complex.png
importance: 3
category: work
giscus_comments: false
---
[Lecture Notes - An Introduction to Topological Data Analysis]({{ site.url }}/assets/pdf/intro_tda.pdf)

During my time as a university lecturer, I was also teaching within the continuous education Master's programme "Data Science - From Mathematical Foundations
to Applications". Typically within the second semester, I taught a lecture on topological data analysis within the unsupervised learning module. 

My notes provide an introduction into this exciting modern field of mathematics, while focusing on an intuitive approach, describing the underlying geometrical ideas instead of rigourous proofs, making them suitable for non-mathematicians. 

The topics include filtrations, persistence diagrams, Wasserstein distances, silhouettes and clustering methods as well as a discussion on how these methods can be applied to analyze grayscale images.

Throghout, each section comes with several examples to grasp the ideas behind the definitions and programming examples in  ```R``` using the [```TDA```](https://cran.r-project.org/web/packages/TDA/index.html) package.

For a bit more sophisticated introduction and more related references, check my [master's thesis]({% link _projects/project_master_thesis.md %}). 

If you are interested in a mathematical rigorous introduction into the beautiful field of algebraic topology - the underlying theory of topological data analysis - then I can highly recommend Rotman's book [An Introduction to Algebraic Topology](https://link.springer.com/book/10.1007/978-1-4612-4576-6).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/complex_raw.png" title="2D point cloud" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/complex.png" title="Czech complex" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, a point cloud in the plane and balls with fixed radius around the points. Right, the corresponding Czech complex for the corresponding radius.
</div>


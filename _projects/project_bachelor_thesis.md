---
layout: page
title: Bachelor's Thesis
description: Dimension splitting combined with Chebyshev tensor approximation.
img: assets/img/order_plot.png
importance: 4
category: study
---
[Bachelor's Thesis - Dimension splitting combined with Chebyshev tensor approximation (German)]({{ site.url }}/assets/pdf/bachelorthesis.pdf)

For my bachelor's thesis I worked on combining dimension splitting methods with Chebyshev tensor approximations in order to numerically solve inhomogenous evolution equations on the unit square $$(0,1)^2$$.

Numerical experiments were conducted in ```Matlab``` using the [```Chebfun```](https://www.chebfun.org/) package.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/pointwise_error.png" title="Pointwise error on the unit square." class="img-fluid rounded z-depth-1" width="250"%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/order_plot.png" title="Achieved order" class="img-fluid rounded z-depth-1" width = "350"%}
    </div>
</div>
<div class="caption">
    On the left, pointwise error on the unit square. Right, the achieved order in the experiment.
</div>

---
layout: page
title: Learning and geometry
description: Constrained policy optimization on submanifolds of stabilizing controllers 
img: assets/img/projects/proj1.png
importance: 1
category: work
---

In this project, we study optimization over the submanifolds of stabilizing 
controllers, equipped with a Riemannian metric arising from constrained Linear 
Quadratic Regulators (LQR) problems. 

Let us illustrate this non-Euclidean geometry in the following example which arises 
from the structure of LQR problem:


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/chal1.pdf" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/chal2.pdf" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/chal3.pdf" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    (Left) An example of the non-convex feasible submanifold of stabilizing controllers. 
    (Center) the orange subset on which the LQR cost has p.d. Euclidean Hessian. 
    (Right) the blue subset on which the the LQR cost has p.d. Riemannian Hessian
</div>



We provide a Newton-type algorithm that enjoys local convergence guarantees and 
exploits the inherent geometry of the problem. Instead of relying on the exponential 
mapping and in the absence of a global retraction, this algorithm revolves around the 
developed stability certificate as well as the linearity of the constraints. 
This idea can be illustrated in the following abstract form: 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/retraction.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/stab-cert.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    (Left) The abstract form of a retraction \( R(G) \) of a 
    tangent vector \( G \) at the point \( K \).
    (Right) The stability certificate \( s_K \) at this point, 
    and the corresponding local neighborhood of origin in \( T_K\mathcal{S} \) 
    for which the retraction is possible.  
</div>


Let us now exemplify the proposed algorithm through numerical simulations in the context of Structured
and Output-feedback LQR problems.



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/landscape_slqr.pdf" title="example image" class="img-fluid rounded " %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/landscape_olqr.pdf" title="example image" class="img-fluid rounded " %}
    </div>
</div>
<div class="caption">
    The trajectories of our algorithm using Riemaninan metric (blue) and 
    Euclidean metric (orange) compared with the Projected Gradient (green)
    for the Strucutred LQR (left) and Output LQR (right) problems.
</div>

<div>
The algorithm at iteration \(t\) updates:
</div>
<div style="text-align:center">
$$K^+ = K + \min\left\{s_{K}, 1\right\} \cdot G$$
</div>
<div>
where \( G \) solves
</div>
<div style="text-align:center">
$$\mathrm{Hess}\, h_{K}[G] = -\mathrm{grad}\, {h}_{K}.$$
</div>

To better see the advantage of using the inherent non-Euclidean geometry, 
we can examine the performance this algorithm for 100 randomly samples parameters
for these problems:


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/random_slqr.pdf" title="example image" class="img-fluid rounded " %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/random_olqr.pdf" title="example image" class="img-fluid rounded " %}
    </div>
</div>
<div class="caption">
    The min, max and median progress of normalized error and cost values  for the
    (left) Structured LQR and (right) Output LQR problems.
</div>



For more details and convergence guarantees, see <a href="https://arxiv.org/pdf/2201.11157.pdf" target="_blank">this paper</a>.


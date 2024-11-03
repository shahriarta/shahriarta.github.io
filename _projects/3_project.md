---
layout: page
title: Geometric Stability Certificate
description: Geometric Innovations in Learning Optimal Policies
img: assets/img/projects/proj1.png
importance: 3
category: not now Geometric methods 
---

This project focuses on advancing methods for solving optimal control problems, particularly emphasizing policy optimization (PO) under constraints. Traditional approaches to stability guarantees have been limited to linear dynamics and quadratic cost structures without constraints. In contrast, this research investigates the non-Euclidean geometry of stabilizing policies for constrained control problems, using the Riemannian geometry inherent in these problems. By incorporating the geometry of the problem, the proposed framework addresses linear constraints on feedback policies while offering efficient numerical schemes for exploring constrained policies.

This work applies to foundational problems like static output-feedback and structured Linear Quadratic Regulator (LQR) problems, as well as complex constraints on input energy that result in nonlinear policy constraints. Future exploration aims to deepen insights into data-guided policy synthesis, particularly by quantifying the inherent difficulty of stabilization problems through the curvature of the manifold of stabilizing policies.

Additionally, the project extends to distributed geometric policy optimization, proposing novel algorithms for consensus on manifolds, distinct from standard consensus methods in Euclidean spaces. Contributions include fast distributed algorithms for the Riemannian center of mass and extending gradient-tracking techniques to Riemannian manifolds. A forthcoming survey, co-authored by leading researchers, will be featured in the Encyclopedia of Systems and Control Engineering.{% cite talebi2022riemannian %}

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/geometry.png" title="example image" class="img-fluid rounded " %}
    </div>
</div>
<div class="caption">
    Geometric policy optimization on submanifold of stabilizing feedback policies.
</div>


Key publications:
<div class="publications">
<p style="margin-top:50px">
{% bibliography --cited %}
</p>
</div>
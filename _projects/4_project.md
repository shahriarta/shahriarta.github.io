---
layout: page
title: 01 - Geometry
description: Studying submanifolds of stabilizing policies for constrained optimal control problems using the Riemannian geometry inherent to the structure of these problems.
img: 
importance: 3
category: current research tracks
---

<figure>
<center>
  <img src="/assets/img/projects/geoemtry_track.png" alt="Geoemtry and Policies" width="750"/>
  <!-- <figcaption>Geoemtry and Policies</figcaption> -->
</center>
</figure>

<p>Iterative stability guarantees are essential in learning optimal policies in control systems, including policy optimization (PO) techniques. This challenge has been examined for problems with linear dynamics and quadratic cost structure (Fazel, et. al., ICML 2018), but in the absence of policy constraints. Furthermore, the non-Euclidean geometry of the stabilization problem in the context of policy optimization has often been overlooked. My research explores submanifolds of stabilizing policies for <em>constrained</em> optimal control problems using the Riemannian geometry inherent to the structure of these problems {% cite talebi2022riemannian %}.</p>

<p><em>Through geometric techniques, this approach handles any linear constraint on the feedback policy under a unifying framework while providing an efficient numerical scheme that searches over the set of constrained stabilizing feedback policies</em>. In addition to addressing foundational problems such as static output-feedback and structured linear quadratic regulator problems, it also facilitates handling intuitive but complicated constraints on the input energy, translated to nonlinear constraints on the policy {% cite talebi2021policy %}.</p>

<p>Furthermore, extending these techniques to <em>distributed</em> geometric policy optimization requires developing fast backbone routines for consensus on manifolds, distinct from the standard consensus on Euclidean spaces. On that line, we have proposed a series of fast distributed algorithms for the Riemannian center of mass {% cite kraisler2023distributed %}, and further considered the case of Lie groups using ideas from gradient tracking but extended to Riemannian manifolds {% cite kraisler2023consensus %}.</p>

<p><strong>Future Directions:</strong> To benchmark these advancements and outline future research, I led a recent survey in collaboration with leading researchers in the field, appearing in the <em>Encyclopedia of Systems and Control Engineering</em> {% cite talebi2024policy %}.</p>

Key publications:
<div class="publications">
<p style="margin-top:50px">
{% bibliography --cited %}
</p>
</div>
---
layout: page
title: Learning to Estimate and Identify
description: Estimating latent variables in dynamical systems is a fundamental challenge in data-driven decision-making, particularly when noise characteristics are unknown.
img: 
importance: 3
category: current research tracks
---

<p>Estimating latent variables is a fundamental challenge in data-driven decision-making, particularly when system characteristics are unknown. The knowledge of noise covariances is often challenging in real-world systems where such statistics are difficult to estimate {% cite zhang2020identification %}. By leveraging the duality between control and estimation, I developed a direct policy optimization framework for optimal estimation in dynamical systems with uncertain dynamics and noisy measurements, even when noise statistics are unknown {% cite talebi2022duality %}. The contributions include analysis of biased gradient estimators under stability constraints, providing non-asymptotic global convergence guarantees that scale logarithmically with system dimension {% cite talebi2023data %}. <em>This work opens the door for data-driven solutions to classical filtering problems, with future directions aimed at nonlinear systems and adaptive filtering in time-varying environments.</em></p>

<p>Building on Willems' Lemma on a parallel track, I have also extended the characterization of exactly how system-theoretic properties and the excitation of input signals relate to <em>the interoperability of every single input-output trajectory</em>, through a complete analysis of reachable, observable, and initial subspaces {% cite yu2021controllability %}. Our results show that data-driven predictive control using online data is equivalent to model predictive control, <em>even for uncontrollable systems</em>.</p>

<p>Extending these results to large-scale systems where high-dimensional noisy data presents a significant challenge in system identification and inference, such as in neuroscience and finance. In this context, my work {% cite zhang2024learning %} <em>makes a significant contribution by addressing the identification of low-dimensional linear time-invariant (LTI) models from high-dimensional noisy observations</em>. We propose a two-stage algorithm that first recovers the high-dimensional observation space and then learns the low-dimensional system dynamics. This achieves an <em>optimal sample complexity and demonstrates that shared structures across systems can further reduce complexity through meta-learning</em>.</p>

Key references:
<div class="publications">
<p style="margin-top:50px">
{% bibliography --cited %}
</p>
</div>

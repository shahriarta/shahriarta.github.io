---
layout: page
title: Risk-sensitive Decision-making
description: A novel approach to long-term risk-sensitive control in stochastic systems through the so-called ergodic-risk criteria
img:
importance: 4
category: current research tracks
---

<p>In stochastic systems, balancing performance with resilience to rare events is critical. Traditional approaches often focus on finite-horizon risk, overlooking long-term cumulative risks unless by imposing strong assumptions on process noise {% cite biswas2023ergodic %}. My recent work {% cite talebi2024uniform %} addresses this by introducing ergodic-risk criteria through probabilistic limiting theorems that can account for noise with unbounded moments. Then through primal-dual optimization techniques, an optimal policy is obtained that balances average performance with ergodic-risk constraints. <em>This extends risk-sensitive methods to a more versatile framework for long-term risk-sensitive control in stochastic systems capable of handling extreme events.</em> Central to my analysis is a tailored Functional Central Limit Theorem (FCLT), where I can establish convergence even in non-stationary environments with heavy-tailed noise.</p>

<p>This is achieved by utilizing ergodic theory {% cite Meyn_Tweedie_Glynn_2009 %}, ensuring uniform ergodicity of controlled processes where stability is maintained even with heavy-tailed noise, provided it has a finite fourth moment.</p>

Key references:
<div class="publications">
<p style="margin-top:50px">
{% bibliography --cited %}
</p>
</div>

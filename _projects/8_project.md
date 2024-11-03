---
layout: page
title: Large-scale Distributed Policy Learning
description: Large-scale distributed policy learning for networked systems utlizing algebraic structures and game theory
img:
importance: 4
category: current research tracks
---

<p>Even though these data-driven techniques are relatively well-studied for linear dynamical systems, they are not directly suitable for networked systems due to the associated computational complexity and information constraints involving the agents' interconnections. To resolve this issue, <em>I characterized inherent symmetries and algebraic patterns, commonly arising in these large-scale complex systems, through the so-called Patterned Linear Semigroups</em> {% cite talebi2021distributed %}. The key idea, allowing us to extend data-driven methods to large-scale complex systems, is that this <em>regular semigroup</em> structure conforms with the construction of policy synthesis through the algebraic relations (e.g., Lyapunov equations). <em>This approach can learn to (almost) optimally control a homogeneous network of dynamical agents only from a sub-network data</em>. Furthermore, this procedure handles attaching/detaching agents on the fly without disrupting learning and control of the entire network {% cite talebi2024data %}.</p>

<p>Additionally, complex dynamical systems often involve interacting agents making decisions for the collective benefit. However, disruptions or adversarial attacks can lead to conflicting decisions. I analyze these processes using cooperative and non-cooperative game theory, where agents adjust their strategies based on available information and environmental effects. My research extends game equilibrium to <em>Noninferior Nash Strategies</em> for agents with linear dynamics and quadratic criteria, providing theoretical guarantees for stability and overcoming attacks {% cite talebi2019cooperative talebi2019decision talebi2017multi %}. I have also developed a simulation platform to efficiently predict outcomes based on system parameters {% cite talebi2018simpe %}.</p>

<p>In emerging resource-sharing enterprises like Uber or Lyft, companies operate over distributed sub-networks where assets are spread across a graph. In these 2-player games, agents lack complete information about their opponent's costs, motivating them to learn optimal strategies directly through their distributed interactions. I developed a no-regret algorithm for learning constrained policies across distributed sub-networks. Framing the problem as Variational Inequalities, each agent updates policies only based on local interactions and its private information, proving the convergent point to be Nash equilibria {% cite talebi2019distributed %}.</p>

<p><strong>Future Directions:</strong> I am building on this work to explore additional algebraic properties and network symmetries, aiming to create a unified framework for distributed reinforcement learning and data-driven control of heterogeneous agents. Also, I investigate non-cooperative settings beyond monotonicity, focusing on equilibria properties and last-iterate convergence that are critical in practical game scenarios beyond just regret minimization.</p>



Key references:
<div class="publications">
<p style="margin-top:50px">
{% bibliography --cited %}
</p>
</div>

---
layout: page
title: 05 - Stabilization
description: A geoemtric approach to fundamental characterization of system-theoretic limitations in online learning and control
img:
importance: 6
category: current research tracks
---

<figure>
<center>
  <img src="/assets/img/projects/stabilization_track.png" alt="Online Stabilization" width="700"/>
  <!-- <figcaption>Online Stabilization</figcaption> -->
</center>
</figure>


<p>Conventional stabilization techniques typically assess control effectiveness <em>asymptotically</em> and often rely on assumptions like knowing <em>a priori</em> that the initial policy is stabilizing or having persistently exciting input-output data. However, many modern applications require high performance in real-time, relying on online data streams. This shift to online stabilization and decision-making highlights the need for a fundamental characterization of system-theoretic limitations in online learning and control from a finite-time perspective. I introduced the concept of <em>regularizability</em> for linear systems, which measures the ability to regulate a system in finite time {% cite talebi2020online %}, contrasting with the traditional asymptotic notions of stabilizability and controllability. Building on this, I proposed a time-varying feedback synthesis procedure that not only regulates the system's state but also generates informative data for use in data-driven control and system identification.</p>

<p>This approach has opened up a number of intriguing design problems using streaming data; for example, it has characterized the properties required to regulate an unstable system on the fly {% cite talebi2021regularizability %}, e.g., an aircraft whose previous control policy has become unstable due to damage or misidentification. In particular, <em>it characterizes a fundamental hardness in any online data-driven stabilization problem.</em></p>


Key references:
<div class="publications">
<p style="margin-top:50px">
{% bibliography --cited %}
</p>
</div>

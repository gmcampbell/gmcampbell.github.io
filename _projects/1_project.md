---
layout: page
title: SPA lifting
description: Mechanical design of soft pneumatic actuators (SPA) for physical human-robot interaction (pHRI).
img: assets/video/100x_gif.gif
importance: 1
category: research
related_publications: true
---

Inverse kinematics can be difficult enough, but what about when the actuator itself deforms? We've characterized a specific class of strain-limited silicone soft pneumatic actuators to enable programmable, passive, force-displacement response to pressure variations.

This is an ongoing research area, but the majority of the work so far can be found in {% cite campbell2025active %} and {% cite campbell2022electroadhesive %}.

In short, we can create safe and inexpesive actuator by trapping air behind a silicone membrane! Theoretically, these can be mass-produced to provide active or passive response to changing air pressure for human-safe motion.

<hr>

Silicone is really stretchy, but we can prevent that stretch (also called 'strain') by embedding fabric in particular locations. Inflating these membranes with pneumatic pressure causes them to expand outward. The following should give you a little idea of how the silicone stretches and inflates:

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SiliconeStretch.gif" title="silicone stretch" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Membrane_Point_Cloud.png" title="membrane point cloud" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/MembraneParameterization.png" title="membrane parameterization and testing" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, we show the passive response of strain-limited silicone to physical deformation. Middle, the 2.5-D shape reponse when the membrane is inflated under positive pneumatic pressure and comes into contact with an external object (measurements in m). Right, a representation and image our characterization of this pneumatic inflation. The testing includes a sensor suite measuring force, pressure, inflation height, and flow rate.
</div>

<hr>

By characterizing the possible lift trajectories, we envision a single pneumatic input allowings for well-supported lifts involving multiple membranes working in parallel. This has been demonstrated with two membranes {% cite campbell2025elastomeric %}.

<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/LiftConcept.png" title="multi-membrane lift concept" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/video/100x_gif.gif" title="leg lift gif" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, a concept drawing for multiple membranes lifting and supporting a human leg. Right, an optimized multi-membrane lift of a mannequin leg (100x speed).
</div>

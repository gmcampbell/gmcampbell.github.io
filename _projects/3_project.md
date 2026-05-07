---
layout: page
title: Design optimization
description: Active learning and Bayesian optimization for mechanical design.
img: assets/video/membrane_plane_flash.gif
# redirect: https://unsplash.com
importance: 2
category: research
related_publications: true
---

Optimization is an over-used term, particularly in mechanical design. Here, our optimization is data-driven, meaning that we are constantly running experiments to optimize our models, and in turn our designs.

Though I am new to the world of machine learning, I have been fortunate to work with some great collaborators and helpful open-source tools. The majority of the work so far can be found in {% cite campbell2025active %} and {% cite campbell2026co %}.

This design process is exciting to me, and I foresee data-informed (and automated) experimentation becoming much more prevalent as the technology develops. I even took part in a <a href="https://soft-ae.seas.upenn.edu/">fellowship</a> around this topic.

<hr>

I've taken two different approaches to learning-enabled design. Bayesian Optimization is focused on maximizing some score (reaching the desired design). Active Learning focuses on exploring the entirety of the design space (and thereby better understanding the system).

<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ParetoFront.png" title="valve design graph" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/GraphicalAbstract.png" title="graphical abstract" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: output from 34 design iterations of soft pneumatic valves. the last datapoint (yellow square) is low and left: it fits the design requirements best! 
    
    Right: graphical abstract detailing the Active Learning design process. Setting design parameters (A), automated experimentation (B), active learning modeling (C), and finally inverse design and verification (D).
</div>

<hr>
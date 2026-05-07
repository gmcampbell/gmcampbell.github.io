---
layout: page
title: Active strain limitation
description: Mechanical design and control for active strain limitation relevant to SPA.
img: assets/video/iPAM_100_5x.GIF
importance: 3
category: research
related_publications: true
# giscus_comments: true
---

Silicone is really stretchy - what about when we don't want it to be? We embed fabric to passively alter the pressure response of the material, but this decision is made at the time of fabrication. With embedded electroadhesive clutches, we can turn those on and off at the speed of electricity!

The majority of the work so far can be found in {% cite campbell2024control %} and {% cite campbell2022electroadhesive %}.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SiliconeStretch.gif" title="silicone stretch" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/clutchLift.gif" title="clutch lift" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/activeDamping.gif" title="active damping" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, we show the passive response of strain-limited silicone to physical deformation. Middle, a commerical clutch from <a href="https://estat.tech/">ESTAT</a> lifts a large weight, even though it's light and flexible. Right, we use that same technology in a silicone wrapper to actively 'dampen' a spring-mass system.
</div>

<hr>

We've used adjustable strain limitation for active shape change, soft actuator position control, and to fling ping-pong balls in the air.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/shapeChange.png" title="shape change" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/positionControl.png" title="clutch position" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pingPong.gif" title="ping pong fling" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, we reach different shapes at identical pressures by (de)activating clutches. Middle, we actively control the position of a soft actuator with varied clutch activation. Right, we rapdily deactivate a clutch and use the stored energy to propel a ping pong ball.
</div>

<hr>
---
layout: distill
title: Drop & Fibre
description: Elastic beam coiling around a drop
img: assets/img/DropFibre.png
importance: 2
category: More
bibliography: CiteOthers.bib
---
Here we study the behaviors of a coupled system : an elastic beam on a drop. This is inspired by the super-extensible spider silk thanks to elasto-capillary interactions. Previous works have already proposed some models to the phenomenon
<d-cite key="elettro_coiling_2015"></d-cite><d-cite key="herve_elettro_elastocapillary_2017"></d-cite>.


In our 2D model, the drop is deformable. The problem is wrtten as a constrained optimisation problem and implemented in Python with <a href='https://web.casadi.org'>CasADi</a>. The video below showing the solution of a set of given material parameters. With different parameter values, the system behaves differently. Hysteresis can be observed. 

<div class="row">
    <div class="col-md-8 offset-md-2">
        {% include video.liquid path="assets/video/DropFibre.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>






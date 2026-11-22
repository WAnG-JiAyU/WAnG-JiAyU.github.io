---
layout: distill # 
title: From growing ring to cable-controlled ring
description: A study of the "growing ring" and the cable-acturated ring
img: assets/img/Elasticring_illustration.png
importance: 1
category: More
bibliography: CiteOthers.bib
---
In this study, we first considered an elastic ring with constant natural curvature and growing length, same as the setup described in the work of Moulton et al<d-cite key="moulton_morphoelastic_2013"></d-cite>.

With dimensional analyses, it can be proved that the deformation is equivalent to an elastic ring with constant length and increasing curvature. 

The theoretical analyses of <a href="https://emiliendilly.github.io/website/">Émilien Dilly</a> give the exact solution of the problem, and show the bending and twisting rigidity affects the buckling behavior. Here is how the bifurcation curves change with the aspect ratio of a rectangular cross-section ring. 
<div class="row justify-content-sm-center">
    <div class="col-md-8 mt-3 mt-md-0">
        {% include video.liquid path="assets/video/Ring/SubSupCritic_woh.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>


Here are basically two types of buckling regimes: the supercritical and the subcritical regimes. For the supercritical regime, all the 3D intermediate states are stable, and we observe graduate deformation from one plan state to the next. For the subcritical regime, the ring goes from one plan state to the next with a sudden jump. Here are two videos of our simulations, formulated as energy minimization problem, compared to the theoretical bifurcation branches. 
<div class="row justify-content-sm-center">
  <div class="col-sm mt-3 mt-md-0">
    {% include video.liquid path="assets/video/Ring/SupCritic_NumTheo.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include video.liquid path="assets/video/Ring/SubCritic_NumTheo.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
  </div>
</div>

Based on the cable-acturated system described <a href="{{ '/projects/10_project/' | relative_url }}">here</a>, we made cable-acturated elastic rings. There are two ways to make a ring with elastic bands and place the cable, we call them the "natural curvature" and "geodesic curvature" cases. Here are two videos of these two setups pulled by a universal test machine, we see different force variations.
<div class="row justify-content-sm-center">
  <div class="col-sm mt-3 mt-md-0">
    {% include video.liquid path="assets/video/Ring/natural_curvature.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include video.liquid path="assets/video/Ring/geodesic_curvature.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
  </div>
</div>

And we also simulated these two cases and the numerical results are very coherent with the experimental measurements. 
<div class="row justify-content-sm-center">
  <div class="col-sm mt-3 mt-md-0">
    {% include video.liquid path="assets/video/Ring/simu_natural_distance.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include video.liquid path="assets/video/Ring/simu_geodesic_distance.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
  </div>
</div>







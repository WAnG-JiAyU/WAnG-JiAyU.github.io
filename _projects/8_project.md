---
layout: distill # 
title: Instabilities in supercritical fluids
description: Numerical study (DNS) of the transition to turbulence in supercritical fluids 
img: assets/img/SetupSupercriticalFluids.png
importance: 4
category: Past

bibliography: CiteOthers.bib
---
This is the project of my research internship with <a href='https://le.ac.uk/people/benjamin-bugeat'>Dr. B. Bugeat</a> in the groupe of <a href='https://www.tudelft.nl/staff/r.pecnik/'>Prof. Pecnik</a>.

In an incompressible isothermal flat-plate boundary layer flow, the unstable eigen-modes known as TS waves, the related secondary modes, and their contributions to the laminar-turbulent transition have long since been investigated. Recently, Ren et al.<d-cite key="Ren_Marxen_Pecnik_2019"></d-cite> discovered a new unstable mode in a boundary layer flow of supercritical CO2. The main objectives of this study are to examine the possible secondary instability related to this newly discovered mode through direct numerical simulation (DNS), analyze the nonlinear effects and resonance interactions which may come along, and finally discuss their potential effects on transition.

Here is the result of one of the simulations.
<!-- <d-footnote>This will become a hoverable footnote.</d-footnote> -->
<div class="row">
    <div class="col-md-8 offset-md-2">
        {% include video.liquid path="assets/video/TS-waves_1.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>

The DNSs are realized through an in-house code in FORTRAN, in which Van der Waals equation of state is used to model the real gas effects brought by the transport and thermodynamic properties of supercritical fluids. After the simulation is initialized by a laminar boundary layer flow, a blowing/suction strip at specific frequencies and amplitudes is applied to trigger instability. 


My work consists of running DNS, collecting data and do analysis with MATLAB. (<a href="/assets/pdf/M2_CM_WANG_rapport_stage_21_22.pdf"> Link to my report</a>)







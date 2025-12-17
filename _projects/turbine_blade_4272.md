---
layout: project
title: MAE 4272 Wind Turbine Blade Design
description: MAE 4272 Wind Turbine Blade Design
technologies: [MATLAB, Autodesk Fusion]
image: /assets/images/turbine.png
---

Project overview:
We designed a wind turbine blade with the objective of maximizing turbine power extraction over a wide range of wind speeds. Our blade is 6 inches long and uses a NACA 4415 airfoil cross-section. We tested the blade in a wind tunnel, and found a peak power extraction of ~1.2 W.

Design process:
We wanted to maximize the theoretical potential power, so we made the blade as large as the constraints allowed for. To maximize the torque on the blade, we designed the twist so that every section along the blade would always be operating at its optimal angle of attack. We designed the chord length along the blade to maximize rotary force and minimmize area. To maximize torque, we also selected a very high operating RPM for the blade. All calculations were done using a MATLAB script that performed an integral analysis on differential sections of the blade.

Testing summary:
We tested the wind turbine in a wind tunnel. We first let the turbine freespin, then we gradually applied a braking torque until the turbine stalled. We reached the upper limit of the torque brake's voltage rating but were unable to stall our turbine. Our turbine had a very high power generation compared to most other turbines of that size. Our operating RPM appeared to be 800 RPM, which was a lot lower than our design intent.

Your contribution:
I wrote the MATLAB scripts that performed the integral analysis on the blade. I wrote the optimization script that determined our blade twist and chord lengths.
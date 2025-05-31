---
permalink: /research/
title: "Research"
author_profile: true
# redirect_from: 
#   - /about/
#   - /about.html
---

## N-body Simulations

Most of my PhD work has been on N-body simulations of self-interacting dark matter (SIDM). I have published a [study on numerical convergence](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.110.123024) in SIDM N-body simulations, where I present choices for particle resolution, timestep size, and gravitational softening length that minimize numerical errors. In this study I found energy non-conservation issues that are still not fully understood in SIDM simulations, and I am investigating these issues in more detail for a future study.

 <figure>
  <img src="https://cmace98.github.io/images/tc_convergence.png" alt="A 4 panel figure showing collapse time convergence as a function of numerical resolution." style="width:100%">
  <figcaption>SIDM core-collapse time converging as a function of particle number N [(link)](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.110.123024).</figcaption>
</figure> 

<!-- ![A 4 panel figure showing collapse time convergence as a function of numerical resolution.](https://cmace98.github.io/images/tc_convergence.png)
*SIDM core-collapse time converging as a function of particle number N [(link)](https://journals.aps.org/prd/abstract/10.1103/PhysRevD.110.123024).* -->

## Gravitational Lensing

<img align="right" src="https://cmace98.github.io/images/convergenceMap.png" alt="My Image" width="40%" height="auto">

I also study the observational signatures of SIDM, specifically the effect of gravothermal core-collapse on gravitational lensing. Core-collapsed halos are very compact objects and strong gravitational lenses. If a lensing galaxy has core-collapsed subhalos they can distort the image, and produce an observable probe of SIDM.

I use my N-body simulations to calibrate models of SIDM and implement those models into the lensing software package [lenstronomy](https://github.com/lenstronomy/lenstronomy). My current project is using these models to test how observable the effects of SIDM on gravitational lenses would be, and testing different core-collapse models to determine the most effecient way to model SIDM halos in lensed systems.
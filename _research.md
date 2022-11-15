---
layout: page
title: Research
permalink: /research/
---
{% include mathjax.html %}

## High Energy Phenomenology (Graduate Research)

My research during graduate school primarily focused on the phenomology of
loosely-bound hadronic moelcules.
To date, there are only two examples of such loosely bound states for a hadron
consisting of two mesons; these are the $X(3872)$ and the $T_{cc}^+(3875)$.
Whether or not these states are in fact an example of a loosely-bound two-body
system, has not reached consensus.
In my work, we assumed the $X$ and $T_{cc}^+$ were loosely-bound meson molecules,
and calculated observables for collider experiments.
The highlight of this research was the acknowledgement of the Landau singularity
in the reation for producing the $X$ or $T_{cc}^+$ and a soft pion.
This singularity, called a triangle singularity, gave a narrow a peak in the
cross section.
Its observation would be a major win for the molecular picture.
$e^+e^-$ experiments should be cable of resolving the peak, and we look forward
to their discoveries.

On the side I also study relativistic hydrodynamics and the evolution of a
quark-gluon plasma produced in heavy-ion collisions.
Although these efforts only received a fraction of my time, they were certainly
more interesting to me.
I had two questions I wanted to answer:
1. What are the dispersion relations for Bjorken-flow
1. How do you compare various hydrodynamic models for Bjorken-flow  

I was never able to answer the first question, but I have not given up on it.
The second question is, however, straightforward to answer thanks to the work
of [Jake Coleman](https://www.proquest.com/docview/2238221111?pq-origsite=gscholar&fromopenview=true).
I developed a Bayesian Model Selection framework using Coleman's ideas.
The repository can be found [here](https://github.com/ominusliticus/Bayesian-BjorkenRTA.git).
This project also served as a proof of 



## High Energy Phenomenology (Post-Doctoral Research)
Ideally, if I get the post-doc I dream of, I will begin to focus my research interest on 
understanding high energy density systems more.
This includes quark-gluon plasmas and nuclear stars.
I believe that there is yet untapped area research that tries to understand spin and angular
momentum evolution in QGPs, though preliminary efforts are underway.
I am particularly interested in applying the language of topological hydro dynamics to 
relativistic spin hydrodynamics and understand if there is any meaningful insight to be gained 
there.

Beyond that, I enjoy understanding physical processes from first principals.
Not model building, and trying to interpret what the underlying physics might be based on
observation.
To this end, understand TMDs and GPDs is on my checklist, unraveling the mysterious of
the non-perturbative structure of hadrons further is on my checklist, and
learning lattice QFT methods is on my checklist.
To the best of my knowledge, no numerical solutions to classical non-Abelian gauge theories
have been made.
I want to understand how to extract topological solutions from differential equations numerically.

### More peripheral ideas
I am currently working on some software called VizQGP that will allow the real-time visualization of
high energy processes such as heavy-ion collisions.
The hope is that this would serve both as an excellent educational tool for science outreach,
assist experimentalists in creating analysis pipelines, and help theorist build intuition 
for themselves.
At its core, the VizQGP will play high energy process like video games where you have
the ability to start and stop the simulation and move around the interaction areas to have
different views of the same process.
The eventual hope is to integrate VizQGP into the existing [art](https://art.fnal.gov/)
framework such that each experiment using the art framework for detector simulation can
have access to real-time events.

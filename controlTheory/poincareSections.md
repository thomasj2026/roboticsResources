# Poincare Sections

## Overview
A Poincare section is a lower-dimensional slice through a system's state space, and the Poincare map records where a trajectory crosses that slice each cycle. It turns the analysis of a periodic orbit into the analysis of a fixed point of a discrete map, so the stability of the orbit can be checked from the map's eigenvalues. In robotics this is the standard way to analyze the stability of periodic gaits in legged robots, such as bipedal walking with impacts at each step.

## Sources
- [Morris and Grizzle, CDC 2005 paper](https://grizzle.robotics.umich.edu/files/CDC_2005_Morris_Grizzle.pdf): a research paper from the Grizzle group at Michigan that applies Poincare-map analysis to determine stable periodic orbits in bipedal robot walking.
- [MIT 12.006J, Nonlinear Dynamics and Chaos (Fall 2022), Lectures 15-16](https://ocw.mit.edu/courses/12-006j-nonlinear-dynamics-chaos-fall-2022/mit12_006jf22_lec15-16.pdf): course lecture notes that introduce Poincare sections and maps as a general tool in nonlinear dynamics.
- [Poincare map notes (UW-Madison, Math 519)](https://people.math.wisc.edu/~angenent/519.2016s/notes/poincare-map.html): short mathematical notes that define the Poincare map and work through its properties.

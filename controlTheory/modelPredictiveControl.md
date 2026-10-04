# Model Predictive Control

## Overview
Model predictive control (MPC) repeatedly solves a finite-horizon optimal control problem using a model of the system, applies only the first control input, and then re-solves at the next time step. Because it handles constraints on states and inputs directly, it is widely used in robotics for trajectory tracking, legged locomotion, drones, and autonomous vehicles.

## Sources
- [Model Predictive Control handout (Purdue)](https://engineering.purdue.edu/~zak/Second_ed/MPC_handout.pdf): a handout that introduces the MPC formulation and how the receding-horizon optimization is set up.

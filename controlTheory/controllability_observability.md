# Controllability and Observability

## Overview
Controllability asks whether inputs can drive a system from any state to any other state, and observability asks whether the full internal state can be reconstructed from the measurements. Together they decide whether state feedback and state estimators (such as Luenberger observers and Kalman filters) can be designed for a given system. In robotics they are checked early in design to confirm that a robot's actuators and sensors are sufficient for the task.

## Sources
- [Introduction to controllability and observability of LTI systems (Purdue handout)](https://engineering.purdue.edu/~zak/Second_ed/hand9_co_and_ob.pdf): a handout that defines both properties for linear time-invariant systems and gives the standard rank tests for checking them.

# Feedback Linearization

## Overview
Feedback linearization is a nonlinear control technique that uses a change of coordinates and a state-feedback law to cancel a system's nonlinearities so the closed loop behaves like a linear system. Once linearized, standard linear tools (pole placement, LQR) can be applied. In robotics it is the idea behind computed-torque control for manipulators, where the known rigid-body dynamics are cancelled to give simple, decoupled joint-space behavior, and it is also used for wheeled robots and quadrotors. Its main limitation is that it depends on an accurate model.

## Sources
- [MIT 6.243J, Dynamics of Nonlinear Systems (Fall 2003), Lecture 13](https://ocw.mit.edu/courses/6-243j-dynamics-of-nonlinear-systems-fall-2003/f6f814332cfeabe65d6a0977711d02ef_lec13_6243_2003.pdf): lecture notes that cover feedback linearization theory for nonlinear systems, from the MIT OpenCourseWare course.

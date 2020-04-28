![SMART 5 NS 16 Comau robot](https://i.ibb.co/nm2GVf0/The-SMART-NS16-industrial-robot-manipulator-W640.jpg)

### Overview

This repository contains the didactic material and source code of three industrial manipulator programming labs developed for the Robot Programming Techniques course held at the University of Genoa in 2012.


### Disclaimer

**This software is released "as is" for academic purposes with no guarantees of any kind. It is not suitable for safe and reliable execution on a real robot. Always follow all safety guidance provided by robot manufacturers and prescribed by applicable laws and regulations when working with real robots, and state-of-the are safety procedures in software development, testing, and deployment.**

### Software
The labs are developed in PDL2, a Pascal-based language developed by Comau (https://www.comau.com/en) for programming its industrial manipulators. The provided labs are based on Comau's C4G motion programming system software.


### Hardware

Labs are compatible with and have been executed on a SMART 5 NS 16 Comau robot.


### Lab 1: Motion Planning Basics

The goal of Lab 1 is to help the class learn to program basic robot motions using the
PDL2 language and the WinC4G environment.

In particular, the following topics are covered:

1) An Introduction to the C4G IDE.
2) Programs and routines.
3) Basic statements, user variables and global variables.
4) Defining a user frame.
5) Motions, paths, and nodes


### Lab 2: PDL2 Program Synchronization

The goal of Lab 2 is to help the class learn to write and execute PDL2 programs that
can run simultaneously while arm control is transferred between them. The use of
conditions, semaphores, and the WAIT and SIGNAL statements is exemplified.

### Lab 3: Pick and Place

The goal of Lab 3 is to help the class learn to write and execute PDL2 programs for pick-
and-place handling tasks. Additionally, the use of priorities for program scheduling
is explored.  

In particular, the lab was intended to have these learning outcomes:

1) How program priorities work and how they interact with motion statements
2) Defining auxiliary frames using saved positions
3) Using the HAND statement to control the gripper
4) Safety measures to be respected during the pick-and-place operations
5) Use of MOVE NEAR and MOVE AWAY
6) Collision detection statements

### References

- PDL2 Language Specs (ITA): http://www.prisma.unina.it/courses/pdl2.pdf

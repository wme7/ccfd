
# CCFD

A two-dimensional finite volume computational fluid dynamics code, written in C

This code will eventually become a drop-in replacement for `cfdfv`, a CFD code written in Fortran by the [Institute of Aerodynamics and Gas Dynamics](http://www.iag.uni-stuttgart.de) at the University of Stuttgart for a CFD programming course. This code itself is not available online, as far as I know, but it is a simplified version of [FLEXI](https://www.flexi-project.org/).

The program uses the [CGNS](https://cgns.github.io/) library version 4.1.0, for storing the calculation results.

## Installation

For now, I have only run it on Linux. Just run `make` in the base directory and everything should compile. However, it should work on MacOS and Windows just as well, maybe some tweaks to the Makefile are necessary. Once a first working version is done, I will worry about other OSs.

## First Step

As a first step I want to recreate the SOD test case. The program output, as well as the calculation output should be the same as the one from `cfdfv`. Although, I want the output to be a little less verbose and the lines should not be longer than 80 characters.

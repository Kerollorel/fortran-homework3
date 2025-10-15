# fortran-homework3

## Description
This repository contains solutions for Homework 3 in Fortran.

### Task 1 — Integer Overflow
Program "overflow.f90" computes factorials using integers of different kinds (`INTEGER(4)` and `INTEGER(8)`) and detects when overflow occurs.

### Task 2 — Loss of Significance
Program "precision.f90" demonstrates loss of significance by repeatedly adding very small numbers to 1.0 until the addition no longer changes the result.  
The step where this happens corresponds to the machine epsilon.

### Task 3 — Reflection
The report "report.txt" contains answers to the reflection questions about numerical limits and errors.

## Compilation
To compile the programs using gfortran:
bash
gfortran -Wall -Wextra -00 overflow.f90 -o overflow
gfortran -Wall -Wextra -00 precision.f90 -o precision

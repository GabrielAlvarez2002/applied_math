Numerical Calculus - Laboratory 1: Numerical Instability & Floating-Point Arithmetic
This repository contains the solutions and Python implementations for Laboratory 1 of the Numerical Calculus course (Licenciatura en Ciencias Matemáticas / Licenciatura en Ciencias de Datos) at FCEN - Universidad de Buenos Aires.
The main objective of this laboratory is to analyze the propagation of rounding errors, the limitations of floating-point arithmetic, and numerical instability through practical implementation and analytical study.

Practice Content
The laboratory covers the implementation in Python of the following exercises focused on numerical analysis and structured programming:

Exercise 1 (Numerical instability of a recurrence):
Exact calculation of I_0 for the definite integral.
Derivation and implementation of the recurrence formula I_n = e - n I_{n-1}.
Analysis of numerical instability when computing successive values up to n = 25.

Exercise 2 (Leap year):
Development of the es_bisiesto(n) function following the rules of the Gregorian calendar.
Verification of test cases (1900, 2000, 2024, and 2025) and total count of leap years between 1 and 2026.

Exercise 3 (Collatz conjecture):
Implementation of the collatz(n) function that generates the sequence until reaching 1.
Graphical visualization of the sequence evolution for n = 27 and analysis of the maximum value reached.
Massive verification of the conjecture for all integers between 1 and 10000, plotting the number of steps.

Exercise 4 (Binary search): 
Implementation of the binary search algorithm busqueda_binaria(lista, v) on sorted lists.
Test runs to verify the correct retrieval of indices.

Technologies Used
Python 3
SymPy / NumPy (for symbolic calculations and numerical handling)
Matplotlib (for sequence visualization plots)



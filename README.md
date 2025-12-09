# ECE240: Introduction to Linear Dynamical Systems  
This repository contains the teaching materials for ECE240, Introduction to Linear Dynamical Systems, at UC Santa Cruz.
I would like to thank my colleagues, Professors Gabe Elkaim and Steve McGuire at UC Santa Cruz, for generously sharing their teaching resources. This course builds upon the Introduction to Linear Dynamical Systems sequence (EE263 and EE363) offered at Stanford University. The lecture notes are adapted from materials developed by Professors Stephen Boyd (Fall 2007) and Sanjay Lall (Fall 2025).


### Key Concepts Overview

This course provides a rigorous and intuitive foundation for analyzing linear dynamical systems using tools from linear algebra, differential equations, optimization, and system theory. The material builds toward a unified understanding of how system structure, eigenvalues, and subspaces determine the behavior, controllability, and observability of dynamical models used in control, robotics, signal processing, and power/energy systems.

---

## Core Mathematical Foundations

- Vector and matrix operations; norms, inner products, inequalities  
- Jacobian and Hessian matrices; Taylor expansions; local linearization  
- Rank, null spaces, projections, eigenvalue and singular value decompositions  
- Pseudoinverses and matrix factorizations (QR, SVD)  

These tools support all later developments in system analysis and optimization.

---

## Linear Dynamical Systems

- Continuous- and discrete-time state-space models  
- Matrix exponential and state transition matrix  
- Homogeneous and forced solutions; convolution representations  
- Stability, system modes, repeated eigenvalues, Jordan blocks  
- Qualitative system behavior via eigenstructure  

Students learn to solve, simulate, and interpret the evolution of LTI systems.

---

## Frequency-Domain and Transfer Function Methods

- Laplace transforms of vector/matrix signals  
- Resolvent \((sI - A)^{-1}\)\ and its poles  
- Transfer functions, impulse responses, input–output behavior  
- Connections between eigenvalues, system stability, and ROC  

---

## Least Squares and Numerical Methods

- Linear least squares, projections, pseudoinverse solutions  
- QR-based solvers, conditioning, numerical stability  
- Statistical interpretations: MLE and BLUE  
- Nonlinear least squares, Gauss–Newton and LM algorithms  
- Bias–variance trade-offs and regularization viewpoints  

These techniques support parameter estimation, system identification, and optimization.

---

## Controllability, Observability, and System Structure

- Controllability and reachable subspaces  
- Observability and state reconstruction  
- Stabilizability and detectability  
- PBH eigenstructure tests  
- Controllability/observability Gramians and minimum-energy control  

These concepts characterize what the system can be driven to do, what can be inferred from measurements, and how structural limitations affect control and estimation.

---

## Learning Outcomes

By completing ECE240, students will be able to:

- Analyze and solve linear dynamical systems using matrix methods  
- Interpret system behavior via eigenvalues, subspaces, and invariants  
- Transition between time-domain and frequency-domain perspectives  
- Formulate and solve linear and nonlinear least-squares problems  
- Determine controllability, observability, stabilizability, and detectability  
- Apply numerical linear algebra tools to modeling, estimation, and control problems  

---



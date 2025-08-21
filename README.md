# LOBSTAH

**L**ibrary for **O**perator-based **B**enchmarks of **S**tochastic/**T**rajectory **A**lgorithms on **H**ardware

LOBSTAH is a modular Python framework for simulating nonlinear, dissipative, and open quantum/classical systems. It provides a unified interface for defining equations, choosing encodings, and running solvers across quantum (Qiskit, PennyLane) and classical backends.

The package is designed for research, benchmarking, and prototyping hybrid quantum–classical algorithms for PDEs/ODEs such as:

Gross–Pitaevskii equation (superfluids, BECs)

Complex Ginzburg–Landau equation

Nonlinear Schrödinger equation

Lindblad master equations

General nonlinear open-system dynamics

## Features

Equations: Built-in support for GPE, CGL, NLS, Lindblad; user-defined PDE/ODEs via a flexible API.

Encodings: Grid, Fourier, lattice (Bose–Hubbard), Carleman/Koopman lifting.

Solvers: Variational Quantum Simulation (VQS), split-step hybrid, Carleman linearization, quantum trajectories, Lindblad variational methods, imaginary-time evolution.

Backends: Qiskit, PennyLane, classical NumPy/SciPy baselines.

Observables & Visualization: Plot densities, phases, entropies, vortex counts, and animate dynamics.

Trajectory Methods: Native support for stochastic unravelings of open-system dynamics.

## Installation

LOBSTAH is under development.

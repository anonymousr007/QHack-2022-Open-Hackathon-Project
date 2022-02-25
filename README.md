<div align='center'>
  
# QHack 2022 Open Hackathon Project: <br>Matrix-Model Simulations using Variational Quantum Eigensolver (VQE)
Team Name: anonymousr007<br>
[Rishabh Singh](https://github.com/anonymousr007)<br>
  
</div>

## Abstract

This project aims to use a truncated (regularized) Hamiltonian for the matrix quantum mechanics models. This Hamiltonian is constructed by considering a truncated Hilbert space in the Fock basis. The truncated Hilbert space is constructed starting from the individual matrix degrees of freedom.

Two types of matrix quantum mechanics models are used

- A Yang-Mills-type bosonic 2-matrix model with SU(2) gauge group, which has 6 bosonic degrees of freedom in total.
- A Supersymmetric 2-matrix model with SU(2) gauge group which corresponds to with the minimal number of degrees of freedom 6 bosons and 3 fermions.

Quantum mechanics with matrix degrees of freedom plays an important role in gauge-gravity duality. Gauge-gravity duality translates difficult problems in quantum gravity to well-defined problems in non-gravitational quantum theories. Although it originated from string–M-theory, connections to various other fields, including 

- Quantum Information Theory
- Condensed Matter Theory
- Cosmology
- Holographic simulation of Quantum Black Holes
- Complex high-dimensional supergravity theories

We use the **Variational Quantum EigenSolver (VQE)** to estimate the low-energy spectrum As for the VQE, the specific architecture that we use does not show a satisfactory performance at strong coupling, perhaps due to the variational forms parametrized by the quantum circuits not adequately probing the full gauge-invariant Hilbert space. This result shows that going beyond the VQE and using more complicated or fully quantum algorithms is not the correct way to approach matrix quantum mechanics for now, because they would require even deeper quantum circuits that are more prone to noise on actual quantum hardware.

## References 

- [Matrix Model simulations using Quantum Computing](https://arxiv.org/abs/2108.02942)


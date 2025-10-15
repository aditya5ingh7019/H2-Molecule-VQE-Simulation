# H2-Molecule-VQE-Simulation
Simulation of H₂ molecule using VQE algorithm with Qiskit
# H₂ Molecule VQE Simulation using Qiskit

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Qiskit](https://img.shields.io/badge/Qiskit-1.0+-blue.svg)](https://qiskit.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A comprehensive quantum simulation of the Hydrogen molecule (H₂) using the Variational Quantum Eigensolver (VQE) algorithm implemented in Qiskit.

##  Overview

This project demonstrates quantum computational chemistry by simulating the H₂ molecule's bond dissociation curve using quantum algorithms. The molecular Hamiltonian is derived using the STO-3G minimal basis set, and ground state energies are computed using VQE on quantum simulators.

##  Features

- **Quantum Chemistry Simulation**: Full H₂ molecular Hamiltonian in STO-3G basis
- **VQE Implementation**: Variational Quantum Eigensolver with customizable ansatzes
- **Bond Dissociation Analysis**: Complete potential energy surface calculation
- **Error Analysis**: Comparison with exact diagonalization results
- **Publication-Ready Plots**: Professional visualization of results
- **Modular Design**: Well-structured, reusable codebase

##  Quick Start

### Installation

```bash
# Clone repository
git clone https://github.com/yourusername/H2-Molecule-VQE-Simulation.git
cd H2-Molecule-VQE-Simulation

# Create conda environment
conda env create -f environment.yml
conda activate h2-vqe

# Or install via pip
pip install -r requirements.txt

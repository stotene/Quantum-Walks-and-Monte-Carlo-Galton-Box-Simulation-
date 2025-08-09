# Quantum Walks and Monte Carlo: Galton Box Simulation

This repository contains my capstone project for the Womanium & WISER Quantum Program 2025, where I implemented both the classical Monte Carlo and quantum walk versions of the Galton Box (Plinko machine). The project demonstrates how quantum principles like superposition and interference affect probability distributions compared to classical randomness.

---

Project Overview

The Galton Box is a statistical device where particles drop through multiple layers of pins, randomly moving left or right, eventually forming a binomial distribution.  
In this project, I:
- Built a classical Monte Carlo simulation using Python and NumPy.
- Designed a quantum version using Qiskit and PennyLane with **Hadamard-based quantum walks**.
- Developed a biased rotation gate (`RY(θ)`) to simulate asymmetrical left/right probabilities.
- Compared results to highlight differences between classical randomness and quantum interference.

---

Key Concepts

- Monte Carlo Simulation – Random sampling for statistical modeling.
- Quantum Walks – Quantum analogues of random walks, using superposition.
- Biased Rotation Gates – Control movement probabilities by adjusting `RY` rotation angles.
- Qiskit & PennyLane – Quantum computing frameworks for simulation and visualization.

---

## Repository Structure
Quantum-Walks-and-Monte-Carlo-Galton-Box-Simulation
├── classical_galton_box.py # My classical Monte Carlo simulation
├── quantum_galton_box.py # My quantum walk simulation
├── biased_rotation_gate.ipynb # Biased RY gate demonstration
├── results/ # Output plots and data
├── README.md # Documentation
└── requirements.txt # Dependencies


---

## Installation
```bash
git clone https://github.com/stotene/Quantum-Walks-and-Monte-Carlo-Galton-Box-Simulation.git
cd Quantum-Walks-and-Monte-Carlo-Galton-Box-Simulation
pip install -r requirements.txt

Dependencies:

numpy

matplotlib

qiskit

pennylane

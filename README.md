# 🎲 Classical Galton Box Simulation (Plinko) using Python

This project simulates a Galton Box (also known as the Plinko game) using classical Monte Carlo methods in Python. It models how particles randomly fall through pegs, making left/right decisions at each level, ultimately forming a binomial distribution — a foundational concept in both classical and quantum statistics.

> This simulation sets the stage for building a Quantum Galton Box using Quantum Walks in Qiskit.

---

## Project Goals

- ✅ Simulate the classical Galton Box using Python
- ✅ Understand Monte Carlo behavior and probability distributions
- ✅ Visualize how random walks lead to binomial outcomes
- 🔜 Prepare for quantum implementation using Qiskit

---

## Background

A Galton Box is a simple device invented by Sir Francis Galton that demonstrates how individual random events aggregate into a predictable distribution. At each level, a particle randomly chooses left or right. The final position depends on how many right moves were made, producing a binomial (or approximately normal) distribution.

---

## Tools & Libraries

- Python 3.x
- NumPy
- Matplotlib
- Qiskit (for quantum extension in later stages)

Install dependencies using:

```bash
pip install numpy matplotlib qiskit

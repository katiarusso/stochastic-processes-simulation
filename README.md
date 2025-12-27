# Hopfield Network: Simulation and Retrieval (Deterministic + Metropolis)

Final project for the course **Stochastic Processes and Simulation in Natural Sciences**.

This repository studies associative memory in the Hopfield model:
- **Deterministic dynamics (T = 0)**: convergence, energy decrease, overlap increase, and error reduction.
- **Metropolis dynamics (finite temperature)**: sampling from the Boltzmann distribution and retrieval performance vs load.
- **Capacity analysis**: retrieval probability as a function of the load $\alpha = \frac{P}{N}$, including comparisons across $N$ and $\beta$.

## Repository structure
- `notebooks/` – Jupyter notebook with simulations and analysis
- `figures/` – saved plots used to summarize results

## How to run
Install dependencies:
```bash
pip install -r requirements.txt
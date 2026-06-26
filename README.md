# trust-polarization-model
Simulation notebook for a philosophy master’s thesis on trust, polarization, and network structure.
This repository contains a cleaned Jupyter notebook with the simulation code used for my master’s thesis in philosophy at the University of Tilburg, Department of Philosophy (2026).

The model explores how network structure affects trust-based polarization among epistemic agents, based on O'Connor and Weatherall's 2018 model on trust based discounting.

## File

- trust_polarization_model_polished.ipynb — main simulation notebook

## How to use

For a first test, run only these sections:

1. Setup
2. Function definitions
3. Quick check: one simulation

Do not run the entire notebook immediately on a first pass. Some later cells contain longer thesis experiments and exploratory parameter sweeps, these exepiments might run into several hours of simulations. If a cell is stuck running, lower the number of runs, agents, or ticks.

## Requirements

- Python 3
- Jupyter Notebook
- numpy
- networkx
- matplotlib
- pandas
- seaborn
- IPython

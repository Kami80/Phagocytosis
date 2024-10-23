# Chemotaxis and Adhesion for Rod-Shaped Beads

This repository contains a Python implementation of a mathematical model that simulates the chemotactic behavior and adhesion dynamics of rod-shaped beads in a two-dimensional space. The model incorporates diffusion, chemotaxis, and adhesion mechanisms to study the interactions between prey and predator particles.

## Requirements
- numpy
- matplotlib
- scipy

## Installation
You can install the required packages using pip:
```bash
pip install numpy matplotlib scipy
```
## Usage
Run the script to simulate the chemotaxis and adhesion dynamics:

The results will be visualized as contour plots showing the densities of prey and predator over time.

## Description
- Parameters: The model includes parameters for diffusion coefficients, chemotactic sensitivity, absorption rates, and adhesion functions.
- Equations: The differential equations are solved using the solve_ivp function from SciPy.
- Initial Conditions: The model starts with predefined densities for prey and predator particles.
## Visualization
The results are plotted at various time points to illustrate the evolution of densities in the simulation.

## License
This project is licensed under the MIT License.

# schrodinger-equation-solver.
# 1D Schrödinger Equation Solver – Infinite Square Well

## Project Description
This project numerically solves the **1D time-independent Schrödinger equation (TISE)** for a particle in an **infinite square well** using Python. It demonstrates fundamental concepts of **quantum mechanics**, including **energy eigenvalues, wavefunctions, and normalization**.  

The solution uses the **finite difference method (FDM)** to discretize the Hamiltonian and solve the eigenvalue problem.

---

## Key Features
- Calculates the first several **energy eigenvalues** and corresponding **wavefunctions**.  
- Plots **normalized wavefunctions** superimposed with energy levels.  
- Fully self-contained **Python script** (`.py`) or **interactive notebook** (`.ipynb`).  
- Modular and extendable for other potentials such as **finite square well** or **harmonic oscillator**.  

---

## Physics Background
The 1D TISE:

$$
-\frac{\hbar^2}{2m} \frac{d^2 \psi(x)}{dx^2} + V(x)\psi(x) = E \psi(x)
$$

Where:  
- \( \psi(x) \) = wavefunction  
- \( V(x) \) = potential (0 inside infinite well, ∞ outside)  
- \( E \) = energy eigenvalue  
- \( \hbar \) = reduced Planck constant  
- \( m \) = particle mass  

---

## How It Works (Algorithm)
1. Discretize space into N points.  
2. Construct the **Hamiltonian matrix** using finite differences.  
3. Solve the **eigenvalue problem** \( H \psi = E \psi \).  
4. Normalize the wavefunctions and plot them along with the energy levels.  

---

## Tools and Libraries Used
- Python 3  
- NumPy (numerical calculations)  
- Matplotlib (plots)  
- SciPy (eigenvalue solver)  

---

## Usage
1. Open the script (`infinite_well.py`) or notebook (`infinite_well.ipynb`).  
2. Run all cells to generate **plots of the first few eigenfunctions**.  
3. Modify **N, L, or potential parameters** to explore other configurations.  

---


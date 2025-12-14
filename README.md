# Rod-Pendulum System Analysis

## Project Overview
This project models and simulates the dynamics of a complex mechanical system consisting of a massless rod pivoting at the origin with two pendulums attached to its ends. The study explores the system's behavior under gravity, ranging from predictable linear motion to chaos.

## Key Features
* **Mathematical Modeling:** Identifies generalized coordinates ($\theta, \phi_1, \phi_2$) and analytically constructs the Lagrangian and equations of motion using **SymPy**.
* **Numerical Simulation:** Solves the system of differential equations numerically using **SciPy** integrators (`odeint` and `solve_ivp`), comparing their performance and accuracy.
* **Chaos & Stability Analysis:** Investigates system evolution under various initial conditions to demonstrate both stable oscillations and chaotic trajectories.
* **Validation:** Verifies the physical accuracy of the simulation by analyzing the time evolution of the total energy of the system.
* **Visualization:** Includes time-series plots of generalized coordinates and energy conservation, alongside animations of the system's movement in the 2D plane.

## Tools Used
* **Python**
* **SymPy** (Symbolic Mathematics)
* **SciPy** (Numerical Integration)
* **NumPy** (Numerical Computing)
* **Matplotlib** (Data Visualization)

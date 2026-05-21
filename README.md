# Radioactive Decay Simulation

This project is a Computational Physics laboratory experiment based on solving radioactive decay systems using Euler’s Numerical Method in Python.

The notebook simulates two different decay models:

1. Mutual Decay System  
   $A \leftrightarrow B$

2. One-Way Decay Chain  
   $A \rightarrow B \rightarrow Decay$

The project uses coupled differential equations to study particle population changes over time and visualize equilibrium behavior.

---

## Topics Covered

- Euler’s Method
- Ordinary Differential Equations (ODEs)
- Radioactive Decay Simulation
- Numerical Methods
- Scientific Plotting using Matplotlib

---

## Equations Used

### Mutual Decay System

$$
\frac{dN_A}{dt} = -\lambda_A N_A + \lambda_B N_B
$$

$$
\frac{dN_B}{dt} = \lambda_A N_A - \lambda_B N_B
$$

### One-Way Decay Chain

$$
\frac{dN_A}{dt} = -N_A
$$

$$
\frac{dN_B}{dt} = N_A - N_B
$$

---

## Technologies Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Features

- Numerical solution of coupled ODEs
- Simulation of radioactive decay systems
- Graphical visualization of particle populations
- Comparison of different decay ratios
- Study of equilibrium and asymptotic behavior

---
## Conclusion

This project demonstrates how computational methods can be used to solve physical systems numerically. Using Euler’s Method, the simulation successfully models radioactive decay behavior and helps understand equilibrium dynamics in coupled systems.

---

# Projectile Motion Simulation using Euler's Method

This project is a Computational Physics simulation of projectile motion using Python and Euler’s Numerical Method. The simulation studies the motion of a projectile both with and without air resistance and compares their trajectories.

---

## Objective

To numerically simulate projectile motion and analyze the effect of air resistance on:

- Trajectory
- Maximum height
- Time of flight
- Horizontal range

---

## Given Parameters

- Initial velocity: $v_0 = 100 \, m/s$
- Gravitational acceleration: $g = 10 \, m/s^2$
- Air resistance coefficient:

$$
\frac{B^2}{m} = 10^{-5}
$$

- Different projection angles: $\theta_1, \theta_2, \theta_3$

---

## Equations of Motion

Position equations:

$$
\dot{x} = v_x
$$

$$
\dot{y} = v_y
$$

### With Air Resistance

$$
\dot{v_x} = -kvv_x
$$

$$
\dot{v_y} = -g - kvv_y
$$

where

$$
v = \sqrt{v_x^2 + v_y^2}
$$

### Without Air Resistance

$$
\dot{v_x} = 0
$$

$$
\dot{v_y} = -g
$$

---

## Technologies Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Features

- Projectile trajectory simulation
- Motion with and without air resistance
- Numerical solution using Euler’s Method
- Graphical visualization of trajectories
- Comparison of different launch angles

---

## Observations

- Without air resistance, the projectile follows a perfect parabolic path.
- Air resistance reduces both the maximum height and horizontal range.
- Trajectories become asymmetric due to drag force.
- The angle giving maximum range decreases when air resistance is present.

---

## Conclusion

This project demonstrates how Euler’s Method can be used to numerically solve equations of motion in projectile dynamics. The simulation clearly shows the physical effects of drag force and highlights the importance of numerical methods in Computational Physics.

---

## How to Run

Clone the repository:

```bash
git clone <repository-link>
```

Install required libraries:

```bash
pip install numpy matplotlib jupyter
```

Run the notebook:

```bash
jupyter notebook
```

---


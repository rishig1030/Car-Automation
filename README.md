<img width="640" height="480" alt="mpc car fig1" src="https://github.com/user-attachments/assets/bc5d916b-1523-4e00-a241-d6e68634226f" /># **🚗Car Automation & UAV Quadcopter Drone Simulation using Model Predictive Control (MPC)**


## 📌 Overview

This project presents a Python-based simulation model for Car Automation using Model Predictive Control (MPC).

The objective is to demonstrate how MPC can be applied to autonomous vehicles for tasks such as lane keeping, lane changing, and trajectory tracking, while respecting physical and safety constraints.

Model Predictive Control (MPC) is a control strategy that predicts the future states of the system over a finite horizon and optimizes control actions by minimizing a cost function. It allows for smooth, stable, and constraint-aware vehicle control..


## Feature :-

✨ Features

✅ Kinematic/Dynamic car modeling in Python.

✅ Lane-keeping and lane-changing simulation.

✅ Path-following with minimal tracking error.

✅ Constraint handling for steering angle and velocity.

✅ Visualization of: Vehicle trajectory , Steering input vs time , Lateral error convergence



## 🛠️ Technologies Used :-

Programming Language: Python 3.x

Libraries:

numpy – Numerical computations

scipy – Linear algebra & ODE solving

matplotlib – Visualization (2D plots)

cvxpy / osqp – Optimization solver for MPC

control – (optional) Control system modeling




## 📊 Results :-

The MPC-based controller is able to:

Follow a predefined path with high accuracy.

Perform smooth lane changes while minimizing lateral error.

Respect steering and velocity constraints.

Simulation outputs include:

<img width="1366" height="673" alt="MPC Car" src="https://github.com/user-attachments/assets/6982b364-3f04-4ae3-8179-0cb6dfcc3df2" />

<img width="640" height="480" alt="mpc car fig2" src="https://github.com/user-attachments/assets/f93010d9-527f-4c95-9d26-6d6bac9fb3ee" />




## 🔮 Future Improvements

Implement Nonlinear MPC (NMPC) for more accurate vehicle dynamics.

Introduce disturbances (wind, road friction) for robustness testing.

Add obstacle avoidance capability.

Extend to multi-vehicle coordination.

# Implementation-of-a-SQP-for-Non-Linear-Optimal-Control
ROB 6323 Reinforcement Learning and Optimal Control for Robotics || Series 2 - SQP || Fall 2024

## **Abstract**  
This project implements a **Sequential Quadratic Programming (SQP)** solver for nonlinear optimal control, applied to a pendulum system. The objective is to find an optimal control sequence that moves the pendulum from its downward position to an upright stance while minimizing control effort. The problem is formulated as a constrained optimization task, solved using **Quadratic Programming (QP) subproblems**.  

Two cases are considered:  
1. **Case 1 (Without Constraints)** – The pendulum is controlled without explicit constraints on torque input.  
2. **Case 2 (With Constraints)** – A maximum allowable control input is enforced to reflect realistic actuator limits.  

The implementation includes mathematical modeling, numerical optimization, and visualization of the pendulum's motion. The code is written in Python using **qpsolvers, cvxopt, and matplotlib** for analysis and simulation.

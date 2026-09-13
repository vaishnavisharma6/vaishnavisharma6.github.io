---
layout: page
title: Research
permalink: /work/
---

# Works
1. ***Minimum-Energy Control For Stochastic Linear Systems***, Submitted to IEEE Control Systems Letters + American Control Conference, 2027.

Vaishnavi Sharma, Vaibhav Katewa

***Abstract***

The open-loop minimum-energy control (MEC) problem asks for control inputs that minimize the control energy while ensuring the terminal state reaches a desired value. In this paper, we study the open-loop MEC problem for stochastic linear time-invariant systems. We consider a variety of stochastic constraints that enforce the terminal error to be small, and show that Stochastic MEC (SMEC) problem can be formulated as a QCQP. We obtain the optimal solution for SMEC and show that it generalizes the well-known Deterministic MEC problem by introducing novel stochastic variants of controllability and Gramian matrices. Finally, we show that there exists a fundamental lower bound on the optimal control energy which cannot be overcome by increasing the time horizon of the problem. 



2. ***Data driven Minimum-Energy Control for Stochastic Linear dynamical systems***, Submitted to IEEE Transactions on Automatic Control.

Vaishnavi Sharma, Vaibhav Katewa

***Abstract***

Minimum energy control (MEC) admits a closed-form solution for deterministic linear systems. However, under stochastic dynamics, presence of process noise raises feasibility questions. In this work, we formulate the MEC problem for stochastic linear systems under probabilistic terminal-state constraints and hard constraints. We derive explicit feasibility conditions based on the non-centrality parameter of a non-central chi-square distribution, obtain a closed-form analytical solution by introducing stochastic equivalent of a T-step Gramian and Controllability matrix, characterize its dependence on the prediction horizon and establish a convergence and lower bound on attainable optimal cost with increase in time horizon. We then extend the formulation to systems with unknown dynamics using structure-aware maximum-likelihood estimation and conformal calibration, and compare these approaches with direct sample-based estimation and probabilistic reformulations. Further, with the help of bias-variance analysis, we show when incorporating structural information proves to be better than direct sample based approach. Finally, we establish finite-sample high-probability upper bounds on parameter estimation error, and optimal-cost sub-optimality, quantifying their dependence on the number of experiments, number of samples per experiment, system dimension, input sequence dimension, and noise to signal ratio. Using simulations, we validate the theoretical results numerically.

***In progress***

1. ***Online Uncertainty propagation for Stochastic MPC using Conformal Prediction.*** \\
2. ***Structure aware Bayesian Optimization for High Dimensional SMPC.***

Vaishnavi Sharma, Vaibhav Katewa

***Brief Abstract***

In this work, We consider minimum energy control problem with unknown cost function setting and leverage
the insights gained in known dynamics and cost setting to design a structure-aware Bayesian optimization
framework (specifically using GP-UCB algorithm). By restricting the search to a lower-dimensional, dynamically relevant subspace, our approach effectively mitigates the curse of dimensionality and significantly improves accuracy. 
---
layout: page
title: Research
permalink: /work/
---

# Works

1. ***Chance constrained minimum energy control for stochastic linear dynamical systems *(Submitted to IEEE Transactions on Automatic Control)***

***Abstract***

Minimum-energy control admits a closed-form solution for deterministic linear systems, but the presence of process noise introduces feasibility questions under stochastic dynamics. In this work, we study this problem in two settings: (a) known dynamics and cost, and (b) unknown dynamics with known cost parameter.
In the known dynamics setting, we formulate the problem using chance constraints and compare it with hard-constraint formulations. We derive explicit feasibility conditions characterized via the non-centrality parameter of a non-central chi-square distribution, obtain a closed-form solution, and analyze it with time horizon.
In the unknown dynamics setting, we develop data-driven approaches based on structure-aware maximum likelihood estimation, direct sample based estimation, and reformulation of chance constraint using euclidean conformal calibration, all of which leverage the linear structure of the system to learn minimum-energy control sequence. Conformal calibration formulation helped in a simpler constraint reformulation and reduction in probability of getting an infeasible solution as optimal solution. We further establish high probability upper bounds on the error in optimal cost and estimated parameters in terms of the number of samples, experiments, system dimension, and noise covariance matrix. Further, with the help of bias-variance analysis and numerical experiments, we show when incorporating structural information proves to be better than direct sample based algorithms.

***In progress***

1. ***Online Uncertainty propagation for Stochastic MPC using Conformal Prediction.***\\
2. ***Bayesian Approach to learn Minimum Energy control for stochastic dyanmical systems.***
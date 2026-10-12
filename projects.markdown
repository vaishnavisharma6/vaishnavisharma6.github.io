---
layout: page
title: Research
permalink: /work/
---

<div class="research-page" markdown="1">

I'm interested in various aspects of decision making under uncertainty. Specifically, I focus on sample efficient learning and uncertainty quantification. Some areas I like, have extensively explored and am working on can be described using these keywords: Bayesian Optimization, Gaussian Processes, Conformal Inference under distribution shift, Online statistical learning, Data-driven stochastic control, Finite sample guarantees, etc.

Some of my works are mentioned below:

## Manuscripts and Preprints

<div class="paper" markdown="1">

### Minimum-Energy Control for Stochastic Linear Systems

**Vaishnavi Sharma**, Vaibhav Katewa

<p class="paper-status">Submitted to IEEE Control Systems Letters (L-CSS) + American Control Conference (ACC), 2027.</p>

<div class="paper-links">
  <a href="https://arxiv.org/abs/2610.13424" target="_blank" rel="noopener noreferrer">arXiv</a>
  <a href="https://github.com/USERNAME/REPO" target="_blank" rel="noopener noreferrer">Code</a>
</div>

<details markdown="1">
<summary>Read abstract</summary>

The open-loop minimum-energy control (MEC) problem asks for control inputs that minimize the control energy while ensuring the terminal state reaches a desired value. In this paper, we study the open-loop MEC problem for stochastic linear time-invariant systems. We consider a variety of stochastic constraints that enforce the terminal error to be small, and show that the stochastic MEC (SMEC) problem can be formulated as a QCQP. We obtain the optimal solution for SMEC and show that it generalizes the well-known deterministic MEC problem by introducing novel stochastic variants of controllability and Gramian matrices. Finally, we show that there exists a fundamental lower bound on the optimal control energy which cannot be overcome by increasing the time horizon of the problem.

</details>

</div>


<div class="paper" markdown="1">

### Data-Driven Minimum-Energy Control for Stochastic Linear Dynamical Systems with Finite-Sample Guarantees

**Vaishnavi Sharma**, Vaibhav Katewa

<p class="paper-status">Submitted to IEEE Transactions on Automatic Control.</p>

<div class="paper-links">
  <a href="https://arxiv.org/abs/ARXIV_ID" target="_blank" rel="noopener noreferrer">arXiv</a>
  <a href="https://github.com/USERNAME/REPO" target="_blank" rel="noopener noreferrer">Code</a>
</div>

<details markdown="1">
<summary>Read abstract</summary>

Minimum-energy control (MEC) admits a closed-form solution for deterministic linear systems. However, under stochastic dynamics, the presence of process noise raises feasibility questions. In this work, we formulate the MEC problem for stochastic linear systems under probabilistic terminal-state constraints and hard constraints. We derive explicit feasibility conditions based on the noncentrality parameter of a noncentral chi-square distribution, obtain a closed-form analytical solution by introducing stochastic equivalents of a T-step Gramian and controllability matrix, characterize its dependence on the prediction horizon, and establish convergence and a lower bound on attainable optimal cost with increasing time horizon.

We then extend the formulation to systems with unknown dynamics using structure-aware maximum-likelihood estimation and conformal calibration, and compare these approaches with direct sample-based estimation and probabilistic reformulations. Further, with the help of bias-variance analysis, we show when incorporating structural information proves to be better than a direct sample-based approach. Finally, we establish finite-sample high-probability upper bounds on parameter-estimation error and optimal-cost suboptimality, quantifying their dependence on the number of experiments, number of samples per experiment, system dimension, input-sequence dimension, and noise-to-signal ratio. Using simulations, we validate the theoretical results numerically.

</details>

</div>


## Ongoing Research

<div class="paper" markdown="1">

### Online Uncertainty Propagation for Stochastic MPC Using Conformal Prediction

**Vaishnavi Sharma**, Vaibhav Katewa

<p class="paper-status">Work in progress.</p>

Developing data-driven approaches for adaptive uncertainty quantification and risk-aware stochastic model predictive control, with an emphasis on finite-sample statistical guarantees.

</div>


<div class="paper" markdown="1">

### Structure-Aware Bayesian Optimization for High-Dimensional Stochastic Control

**Vaishnavi Sharma**, Vaibhav Katewa

<p class="paper-status">Work in progress.</p>

In this work, We consider minimum energy control problem with unknown cost function setting and leverage
the insights gained in known dynamics and cost setting to design a structure-aware Bayesian optimization
framework (specifically using GP-UCB algorithm). By restricting the search to a lower-dimensional, dynamically relevant subspace, our approach effectively mitigates the curse of dimensionality and significantly improves accuracy.

</div>

</div>

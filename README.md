# SWBBO
Distributionally Robust Bayesian Optimization via Sinkhorn-Based Wasserstein Barycenters
This repository contains the official implementation of the paper:
"Distributionally Robust Bayesian Optimization via Sinkhorn-Based Wasserstein Barycenters"
Overview
This work introduces a novel approach to Bayesian Optimization (BO) that addresses distributional uncertainty in contextual optimization problems. Our method leverages Sinkhorn-based Wasserstein barycenters to create robust acquisition functions that maintain performance under distributional shifts.
Key Contributions

First BO acquisition function based on Sinkhorn-computed Wasserstein barycenters: A principled approach to synthesizing distributional uncertainty while preserving geometric structure
Distributionally Robust Sinkhorn Barycenter UCB (DR-SB-UCB): A robust acquisition function with distributional Lipschitz regularization
Theoretical foundations: Convergence guarantees and approximation bounds for the proposed methodology
Adaptive robustness control: Dynamic mechanisms that balance robustness and optimization efficiency

Related Work
This code builds upon and extends the work presented in:
"Wasserstein Distributionally Robust Bayesian Optimization with Continuous Context" (AISTATS 2025)
Paper available at: https://arxiv.org/abs/2503.20341
Our implementation is based on the repository released by Micheli et al., available at:
[https://github.com/lamda-bbo/sbokde](https://github.com/frmicheli/WDRBO)

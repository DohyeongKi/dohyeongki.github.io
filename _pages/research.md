---
layout: single
title: "Selected Works"
permalink: /research/
author_profile: true
---

## Publications

- **Ki, D.**, Fang, B., and Guntuboyina, A. (2024) MARS via LASSO. Annals of Statistics, 52(3), 1102-1126. [arXiv](https://arxiv.org/abs/2111.11694) [code](https://github.com/DohyeongKi/mars-lasso-paper) [journal](https://projecteuclid.org/journals/annals-of-statistics/volume-52/issue-3/MARS-via-LASSO/10.1214/24-AOS2384.full)
  <div class="header">Abstract</div>
  <div class="content">
    Multivariate adaptive regression splines (MARS) is a popular method for nonparametric regression introduced by Friedman in 1991. MARS fits simple nonlinear and non-additive functions to regression data. We propose and study a natural lasso variant of the MARS method. Our method is based on least squares estimation over a convex class of functions obtained by considering infinite-dimensional linear combinations of functions in the MARS basis and imposing a variation based complexity constraint. Our estimator can be computed via finite-dimensional convex optimization, although it is defined as a solution to an infinite-dimensional optimization problem. Under a few standard design assumptions, we prove that our estimator achieves a rate of convergence that depends only logarithmically on dimension and thus avoids the usual curse of dimensionality to some extent. We also show that our method is naturally connected to nonparametric estimation techniques based on smoothness constraints. We implement our method with a cross-validation scheme for the selection of the involved tuning parameter and compare it to the usual MARS method in various simulation and real data settings.
  </div>

## Preprints

- **Ki, D.** and Guntuboyina, A. (2025+) Totally Concave Regression. Under review. [arXiv](https://arxiv.org/abs/2501.04360) [code](https://github.com/DohyeongKi/tc-reg-paper)
  <div class="header">Abstract</div>
  <div class="content">
    Shape constraints in nonparametric regression provide a powerful framework for estimating regression functions under realistic assumptions without tuning parameters. However, most existing methods—except additive models—impose too weak restrictions, often leading to overfitting in high dimensions. Conversely, additive models can be too rigid, failing to capture covariate interactions. This paper introduces a novel multivariate shape-constrained regression approach based on total concavity, originally studied by T. Popoviciu. Our method allows interactions while mitigating the curse of dimensionality, with convergence rates that depend only logarithmically on the number of covariates. We characterize and compute the least squares estimator over totally concave functions, derive theoretical guarantees, and demonstrate its practical effectiveness through empirical studies on real-world datasets.
  </div>

## Working Papers

- **Ki, D.** and Guntuboyina, A. (2025+) What functions does XGBoost learn? In preparation. 

---

## Work in Progress

- Nearly Log-Concave Density Estimation. With Arlene K. H. Kim and Adityanand Guntuboyina.
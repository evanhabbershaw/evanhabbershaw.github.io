---
title:
layout: default
permalink: /research/
published: true
---

## Research

My primary research interests lie in Computational and Applied Mathematics with an emphasis on numerical methods and theoretical analyses of dynamical systems for dilute gas and plasma mixtures. My secondary research interests are in Mathematical Biology, with an emphasis on vector borne epidemiological models.

### Current Projects

I am currently funded through a DOE grant to develop theory and numerical methods for Bhatnagar-Gross-Krook (BGK) kinetic models, with my advisors Dr. Cory Hauck (ORNL) and Dr. Steven Wise (UTK). In particular, I have developed implicit-explicit (IMEX) numerical methods for the standard BGK model, and have been studying multi-species kinetic models (including multi-species versions of BGK, ellipsoidal statistical BGK, and Fokker--Planck type models), and developing general theory and numerical methods for these models of gas and plasma mixtures. Beyond these models, I am exploring fundamental modeling of particle mixtures via the multi-species Boltzmann model, aiming to develop a comprehensive framework for this prototypical system.

#### Multi-Species BGK Modeling and Numerical Methods

For the (space homogeneous) multi-species BGK (M-BGK) moment system of equations, I have proved existence and uniqueness of solutions, and established bounds on the asymptotic relaxation of the solution to constant steady state values. (SIAM Journal on Applied Mathematics (SIAP) [DOI Link](https://doi.org/10.1137/23M1596314); [arXiv.org preprint here](https://arxiv.org/abs/2310.12885).)

On the numerical side, I have developed an IMEX method that computes the implicit update of the moment equations using a nonlinear iterative solver to compute the implicit step for the collision operator. (Article accepted for publication at SIAM Journal on Numerical Analysis (SINUM); see the [arXiv.org preprint here](https://arxiv.org/abs/2404.11775).)

#### Multi-Species Fokker--Planck Model

More recently, I have been working on a Fokker--Planck type model for charged particle plasma dynamics. The model allows for added freedom in the choice of parameters, which facilitates matching the momentum and temperature relaxation rates of the multi-species Boltzmann Equation with Coulomb potentials. The conservation, entropy dissipation, and equilibrium properties (H-Theorem) of the model have been established in our submitted paper. (Article in review at Journal of Statistical Physics; see the [arXiv.org preprint here](https://arxiv.org/abs/2404.11775).)


### Recent Collaborators

[Cory Hauck (Oak Ridge National Laboratory)](https://www.ornl.gov/staff-profile/cory-d-hauck)

[Steven Wise (University of Tennessee, Knoxville)](https://stevenmwise.github.io/)

[Jingwei Hu (University of Washington, Seattle)](https://jingweihu-math.github.io/webpage/)

[Jing Li (California State University, Northridge)](http://www.csun.edu/~jingli/)
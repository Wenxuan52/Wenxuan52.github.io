---
title: "Physics-guided multistage neural network: A physically guided network for step initial values and dispersive shock wave phenomena"
collection: publications
category: journal
permalink: /publication/2024-11-01-physics-guided-multistage
date: 2024-11-01
venue: 'Physical Review E'
authors: 'Wenxuan Yuan, Rui Guo'
paperurl: True
github: True
---

## Abstract

The phenomenon of dispersive shock waves (DSWs) exerts a critical influence on nonlinear dynamics in various nonlinear fields, and simulating this complex physical process remains a significant challenge. In this paper, we dramatically enhance the ability of physics-informed neural networks (PINNs) to describe complex dispersive phenomena by integrating residual learning paradigms and introducing a dispersion factor into the existing PINN method. For iteration problems in the time domain, we propose a highly adaptable Deep Runge-Kutta method, which not only ensures high accuracy and flexibility but also facilitates the inference of numerically significant physical state variables. Furthermore, we formulate a physics-guided multistage neural network (PgMSNN) model using a multistage training strategy to address the evolution problem of the generalized Gardner equation with step initial conditions. Representative numerical experiments are conducted in selected regions to study forward problems, model stability, and parameter inversion issues. Comparisons with state-of-the-art numerical simulation neural networks highlight the efficacy of the PgMSNN model in addressing these challenges. This study not only improves the numerical simulation accuracy and stability of PINNs for DSW phenomena but also provides an efficient and flexible tool for the simulation and prediction of complex nonlinear dynamic systems. The successful application of the PgMSNN model highlights the significant potential of physics-guided strategies in deep learning for tackling complex physical problems.

## Resources

- [Paper](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.110.065307)
- [Code](https://github.com/Wenxuan52/PgMSNN)

## Citation

```bibtex
@article{PhysRevE.110.065307,
  title = {Physics-guided multistage neural network: A physically guided network for step initial values and dispersive shock wave phenomena},
  author = {Yuan, Wen-Xuan and Guo, Rui},
  journal = {Phys. Rev. E},
  volume = {110},
  issue = {6},
  pages = {065307},
  numpages = {20},
  year = {2024},
  month = {Dec},
  publisher = {American Physical Society},
  doi = {10.1103/PhysRevE.110.065307},
  url = {https://link.aps.org/doi/10.1103/PhysRevE.110.065307}
}
```
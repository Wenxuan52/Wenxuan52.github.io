---
title: "Physics-informed Neural Network method for the Modified Nonlinear Schrödinger equation"
collection: publications
category: journal
permalink: /publication/2023-05-01-pinn-schrodinger
date: 2023-05-01
venue: 'Optik'
authors: 'Wenxuan Yuan, Rui Guo, Yining Gao'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0030402623002358'
---

## Abstract:

In this paper, we apply the Physics-informed Neural Network (PINN) method to investigate some nonlinear wave solutions of the Modified Nonlinear Schrödinger (MNLS) equation, which characterizes the ultrashort pulse propagation well in optical fibers. We generate the training dataset by the Latin Hypercube Sampling (LHS) method under Dirichlet boundary conditions. We use the Xavier initialization method to generate the parameters of the neural network, and then use the Adam algorithm to optimize them. Finally, we derive the data-driven solutions of single soliton solution, double solitons solution, single breather solution, double breather solution, first-order rogue wave and second-order rogue wave solutions for the MNLS equation. Through loss and L2 error of the experimental results, the PINN method has been verified to have prominent stability and effectiveness.

## Resources

- [Paper](https://www.sciencedirect.com/science/article/pii/S0030402623002358)
- [Code](https://github.com/Wenxuan52/PINN-with-TF-and-Pytorch)

## Citation

```bibtex
@article{YUAN2023170739,
title = {Physics-informed Neural Network method for the Modified Nonlinear Schrödinger equation},
journal = {Optik},
volume = {279},
pages = {170739},
year = {2023},
issn = {0030-4026},
doi = {https://doi.org/10.1016/j.ijleo.2023.170739},
url = {https://www.sciencedirect.com/science/article/pii/S0030402623002358},
author = {Wen-Xuan Yuan and Rui Guo and Yi-Ning Gao},
keywords = {The modified nonlinear Schrödinger equation, The PINN method, Neural network}
}
```
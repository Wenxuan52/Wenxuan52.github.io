---
title: "On Stability and Robustness of Diffusion Posterior Sampling for Bayesian Inverse Problems"
collection: publications
category: preprint
permalink: /publication/2026-02-10-diffusion-posterior
date: 2026-02-10
venue: 'International Conference on Machine Learning (ICML) 2026'
authors: 'Yiming Yang, Xiaoyuan Cheng, Yi He, Kaiyu Li, Wenxuan Yuan, Zhuo Sun'
paperurl: 'https://arxiv.org/abs/2602.02045'
header:
  teaser: publications/diffusion-posterior.png
demo_media: "/images/publications/diffusion-posterior.png"
---

## Abstract:

Diffusion models have recently emerged as powerful learned priors for Bayesian inverse problems (BIPs). Diffusion-based solvers rely on a presumed likelihood for the observations in BIPs to guide the generation process. However, the link between likelihood and recovery quality for BIPs is unclear in previous works. We bridge this gap by characterizing the posterior approximation error and proving the \emph{stability} of the diffusion-based solvers. Meanwhile, an immediate result of our findings on stability demonstrates the lack of robustness in diffusion-based solvers, which remains unexplored. This can degrade performance when the presumed likelihood mismatches the unknown true data generation processes. To address this issue, we propose a simple yet effective solution, \emph{robust diffusion posterior sampling}, which is provably \emph{robust} and compatible with existing gradient-based posterior samplers. Empirical results on scientific inverse problems and natural image tasks validate the effectiveness and robustness of our method, showing consistent performance improvements under challenging likelihood misspecifications.

## Resources

- [Paper](https://arxiv.org/abs/2602.02045)
- [Code](https://github.com/Wenxuan52/ALGD)

## Demonstration

![Project Demonstration]({{ page.demo_media }})

## Citation

```bibtex
@misc{cheng2026doeslagrangianguidesafe,
  title = {How Does the Lagrangian Guide Safe Reinforcement Learning through Diffusion Models?}, 
  author = {Xiaoyuan Cheng and Wenxuan Yuan and Boyang Li and Yuanchao Xu and Yiming Yang and Hao Liang and Bei Peng and Robert Loftin and Zhuo Sun and Yukun Hu},
  year = {2026},
  eprint = {2602.02924},
  archivePrefix = {arXiv},
  primaryClass = {cs.LG},
  url = {https://arxiv.org/abs/2602.02924}, 
}
```
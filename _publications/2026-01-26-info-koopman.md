---
title: "Information Shapes Koopman Representation"
collection: publications
category: conference
permalink: /publication/2026-01-26-info-koopman
date: 2026-01-26
venue: 'International Conference on Learning Representations (ICLR)'
authors: 'Xiaoyuan Cheng, Wenxuan Yuan, Yiming Yang, Yuanzhao Zhang, Sibo Cheng, Yi He, Zhuo Sun'
paperurl: 'https://openreview.net/forum?id=Szh0ELyQxL'
header:
  teaser: publications/infokoopman.png
demo_media: "/images/publications/infokoopman.png"
---

## Abstract:

The Koopman operator provides a powerful framework for modeling dynamical systems and has attracted growing interest from the machine learning community. However, its infinite-dimensional nature makes identifying suitable finite-dimensional subspaces challenging, especially for deep architectures. We argue that these difficulties come from suboptimal representation learning, where latent variables fail to balance expressivity and simplicity. This tension is closely related to the information bottleneck (IB) dilemma: constructing compressed representations that are both compact and predictive. Rethinking Koopman learning through this lens, we demonstrate that latent mutual information promotes simplicity, yet an overemphasis on simplicity may cause latent space to collapse onto a few dominant modes. In contrast, expressiveness is sustained by the von Neumann entropy, which prevents such collapse and encourages mode diversity. This insight leads us to propose an information-theoretic Lagrangian formulation that explicitly balances this tradeoff. Furthermore, we propose a new algorithm based on the Lagrangian formulation that encourages both simplicity and expressiveness, leading to a stable and interpretable Koopman representation. Beyond quantitative evaluations, we further visualize the learned manifolds under our representations, observing empirical results consistent with our theoretical predictions. Finally, we validate our approach across a diverse range of dynamical systems, demonstrating improved performance over existing Koopman learning methods. The implementation is publicly available at this [link](https://openreview.net/forum?id=Szh0ELyQxL).

## Resources

- [Paper](https://openreview.net/forum?id=Szh0ELyQxL)
- [Code](https://github.com/Wenxuan52/InformationKoopman)

## Demonstration

![Project Demonstration]({{ page.demo_media }})

## Citation

```bibtex
@inproceedings{
cheng2026information,
title={Information Shapes Koopman Representation},
author={Xiaoyuan Cheng and Wenxuan Yuan and Yiming Yang and Yuanzhao Zhang and Sibo Cheng and Yi He and Zhuo Sun},
booktitle={The Fourteenth International Conference on Learning Representations},
year={2026},
url={https://openreview.net/forum?id=Szh0ELyQxL}
}
```
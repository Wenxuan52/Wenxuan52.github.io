---
title: "Fisher Decorator: Refining Flow Policy via A Local Transport Map"
collection: publications
category: conference
permalink: /publication/2026-09-25-fisher-decorator
date: 2026-09-25
venue: 'Conference on Neural Information Processing Systems (NeurIPS)'
venue_short: 'NeurIPS'
presentation: 'Poster'
authors: 'Xiaoyuan Cheng, Haoyu Wang, Wenxuan Yuan, Ziyan Wang, Zonghao Chen, Li Zeng, Zhuo Sun'
paperurl: 'https://arxiv.org/abs/2604.17919'
codeurl: 'https://github.com/ARC0127/Fisher-Decorator'
header:
  teaser: publications/fisher-decorator.png
demo_media: "/images/publications/fisher-decorator.png"
demo_tag: "Poster"
---

## Abstract

Recent advances in flow-based offline reinforcement learning (RL) have achieved strong performance by parameterizing policies via flow matching. However, they still face critical trade-offs among expressiveness, optimality, and efficiency. In particular, existing flow policies interpret the <em>L</em><sub>2</sub> regularization as an upper bound of the 2-Wasserstein distance (<em>W</em><sub>2</sub>), which can be problematic in offline settings. This issue stems from a fundamental geometric mismatch: the behavioral policy manifold is inherently anisotropic, whereas the <em>L</em><sub>2</sub> (or upper bound of <em>W</em><sub>2</sub>) regularization is isotropic and density-insensitive, leading to systematically misaligned optimization directions. To address this, we revisit offline RL from a geometric perspective and show that policy refinement can be formulated as a local transport map—an initial flow policy augmented by a residual displacement. By analyzing the induced density transformation, we derive a local quadratic approximation of the KL-constrained objective governed by the Fisher information matrix, enabling a tractable anisotropic optimization formulation. By leveraging the score function embedded in the flow velocity, we obtain a corresponding quadratic constraint for efficient optimization. Our results reveal that the optimality gap in prior methods arises from their isotropic approximation. In contrast, our framework achieves a controllable approximation error within a provable neighborhood of the optimal solution. Extensive experiments demonstrate state-of-the-art performance across diverse offline RL benchmarks.

## Resources

- [Paper](https://arxiv.org/abs/2604.17919)
- [Download PDF](https://arxiv.org/pdf/2604.17919)
- [Code](https://github.com/ARC0127/Fisher-Decorator)

## Demonstration

{% include publication-demo-media.html media=page.demo_media tag=page.demo_tag %}

*Geometric interpretation of policy refinement (Figure 1 of the [paper](https://arxiv.org/abs/2604.17919), CC BY 4.0).*

## Citation

```bibtex
@inproceedings{cheng2026fisher,
  title = {Fisher Decorator: Refining Flow Policy via A Local Transport Map},
  author = {Xiaoyuan Cheng and Haoyu Wang and Wenxuan Yuan and Ziyan Wang and Zonghao Chen and Li Zeng and Zhuo Sun},
  booktitle = {Advances in Neural Information Processing Systems},
  year = {2026},
  url = {https://arxiv.org/abs/2604.17919}
}
```

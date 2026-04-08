---
title: "Efficient Bayesian Estimation of Dynamic Structural Equation Models via State Space Marginalization" 
date: 2026-03-05
lastmod: 2026-03-05
tags: ["DSEM","intensive longitudinal data", "Kalman filter", "Hamiltonian Monte Carlo", "state space model"]
author: [
    "Øystein Sørensen"
]
description: "This paper shows that the within-level part of any dynamic structural equation model can be reformulated as a linear Gaussian state space model, enabling analytical marginalization via a Kalman filter and highly efficient estimation via Hamiltonian Monte Carlo. arXiv preprint."
summary: "This paper shows that the within-level part of any dynamic structural equation model can be reformulated as a linear Gaussian state space model. Consequently, the latent states can be analytically marginalized using a Kalman filter, allowing for highly efficient estimation via Hamiltonian Monte Carlo. This makes DSEM estimation computationally tractable for much larger datasets than what has been previously possible. arXiv preprint."
cover:
    image: ""
    
    relative: false
editPost:
    URL: "https://doi.org/10.48550/arXiv.2603.04003"
    Text: "arXiv"

---

---

##### Download

+ [Paper](https://arxiv.org/abs/2603.04003)

---

##### Abstract

Dynamic structural equation models (DSEMs) combine time-series modeling of within-person processes with hierarchical modeling of between-person differences and differences between timepoints, and have become very popular for the analysis of intensive longitudinal data in the social sciences. An important computational bottleneck has, however, still not been resolved: whenever the underlying process is assumed to be latent and measured by one or more indicators per timepoint, currently published algorithms rely on inefficient brute-force Markov chain Monte Carlo sampling which scales poorly as the number of timepoints and participants increases and results in highly correlated samples. The main result of this paper shows that the within-level part of any DSEM can be reformulated as a linear Gaussian state space model. Consequently, the latent states can be analytically marginalized using a Kalman filter, allowing for highly efficient estimation via Hamiltonian Monte Carlo. This makes estimation of DSEMs computationally tractable for much larger datasets -- both in terms of timepoints and participants -- than what has been previously possible. We demonstrate the proposed algorithm in several simulation experiments, showing it can be orders of magnitude more efficient than standard Metropolis-within-Gibbs approaches.

---

##### Citation

Sørensen, Ø. (2026). Efficient Bayesian Estimation of Dynamic Structural Equation Models via State Space Marginalization. arXiv preprint arXiv:2603.04003. https://doi.org/10.48550/arXiv.2603.04003



```BibTeX
@article{Sorensen2026dsem,
  title = {Efficient Bayesian Estimation of Dynamic Structural Equation Models via State Space Marginalization},
  author = {S{\o}rensen, {\O}ystein},
  year = {2026},
  eprint = {2603.04003},
  archivePrefix = {arXiv},
  primaryClass = {stat.ME},
  doi = {10.48550/arXiv.2603.04003},
  URL = {https://arxiv.org/abs/2603.04003}
}
```


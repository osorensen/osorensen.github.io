---
title: "A Hybrid NUTS-Gibbs Sampler with State Space Marginalization for Estimation of Dynamic Structural Equation Models with Binomial Outcomes" 
date: 2026-03-25
lastmod: 2026-03-25
tags: ["DSEM","intensive longitudinal data", "NUTS", "Gibbs sampler", "Pólya-Gamma", "binomial", "Kalman filter"]
author: [
    "Øystein Sørensen",
    "Ethan M. McCormick"
]
description: "This paper presents a hybrid NUTS-Gibbs sampler for dynamic structural equation models with binomial outcomes. The Gibbs step handles Pólya-Gamma latent variables from a logit link, while the NUTS step uses a Kalman filter to marginalize over latent states. arXiv preprint."
summary: "This paper presents a hybrid sampler -- alternating between one step of the No-U-Turn Sampler (NUTS) and one Gibbs step -- for estimating dynamic structural equation models with binomial outcomes. The Gibbs step handles Pólya-Gamma distributed latent variables arising from a logit link, and the NUTS step uses a Kalman filter to marginalize over latent states. We demonstrate that the proposed sampler makes DSEM estimation with binomial data feasible for larger data and models than previously possible. arXiv preprint."
cover:
    image: ""
    
    relative: false
editPost:
    URL: "https://doi.org/10.48550/arXiv.2603.29647"
    Text: "arXiv"

---

---

##### Download

+ [Paper](https://arxiv.org/abs/2603.29647)

---

##### Abstract

Dynamic structural equation modeling (DSEM) is widely used for analyzing intensive longitudinal data (ILD). Although many ILD have categorical (Bernoulli or binomially distributed) responses, currently available Metropolis-within-Gibbs samplers for estimating DSEMs are limited to using the probit link and the Bernoulli distribution. These samplers scale poorly with increasing model complexity and/or data size. Here, we present a hybrid sampler -- alternating between one step of the No-U-Turn Sampler (NUTS) and one Gibbs step -- which solves both of these problems: the Gibbs step naturally handles Pólya-Gamma distributed latent variables arising from binomially distributed responses with a logit link, and the NUTS step utilizes a Kalman filter to exactly marginalize over latent states, alleviating the need to sample these variables. We demonstrate in simulation experiments that the proposed sampler is more efficient than alternative algorithms, and that it makes DSEM estimation with binomial data feasible for larger data and models than what has previously been possible. We also illustrate its use in an example application of predicting panic attacks.

---

##### Citation

Sørensen, Ø., & McCormick, E. M. (2026). A Hybrid NUTS-Gibbs Sampler with State Space Marginalization for Estimation of Dynamic Structural Equation Models with Binomial Outcomes. arXiv preprint arXiv:2603.29647. https://doi.org/10.48550/arXiv.2603.29647



```BibTeX
@article{Sorensen2026hybrid,
  title = {A Hybrid NUTS-Gibbs Sampler with State Space Marginalization for Estimation of Dynamic Structural Equation Models with Binomial Outcomes},
  author = {S{\o}rensen, {\O}ystein and McCormick, Ethan M.},
  year = {2026},
  eprint = {2603.29647},
  archivePrefix = {arXiv},
  primaryClass = {stat.CO},
  doi = {10.48550/arXiv.2603.29647},
  URL = {https://arxiv.org/abs/2603.29647}
}
```


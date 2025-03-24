---
title: "Sequential Rank and Preference Learning with the Bayesian Mallows Model" 
date: 2024-12-01
lastmod: 2024-07-12
tags: ["Mallows mixtures","partial rankings", "particle filter", "preference learning", "SMC$^{2}$"]
author: [
    "Øystein Sørensen",
    "Anja Stein",
    "Waldir Leoncio Netto",
    "David S. Leslie"
]
description: "This paper considers rank and preference modeling for the case in which data arrive sequentially, rather than in a batch. The goal is to compute the posterior distribution incrementally in time, so that it can be quickly updated when new data arrives. To this end, we develop a sequential Monte Carlo algorithm for the Bayesian Mallows model. arXiv preprint currently under revision."
summary: "This paper considers rank and preference modeling for the case in which data arrive sequentially, rather than in a batch. The goal is to compute the posterior distribution incrementally in time, so that it can be quickly updated when new data arrives. To this end, we develop a sequential Monte Carlo algorithm for the Bayesian Mallows model. arXiv preprint currently under revision."
cover:
    image: "paper11.png"
    
    relative: false
editPost:
    URL: "https://doi.org/10.48550/arXiv.2412.13644"
    Text: "arXiv preprint"

---

---

##### Download

+ [Paper](https://doi.org/10.48550/arXiv.2412.13644)

---

##### Abstract

The Bayesian Mallows model is a flexible tool for analyzing data in the form of complete or partial rankings, and transitive or intransitive pairwise preferences. In many potential applications of preference learning, data arrive sequentially and it is of practical interest to update posterior beliefs and predictions efficiently, based on the currently available data. Despite this, most algorithms proposed so far have focused on batch inference. In this paper we present an algorithm for sequentially estimating the posterior distributions of the Bayesian Mallows model using nested sequential Monte Carlo. As it requires minimum user input in form of tuning parameters, is straightforward to parallelize, and returns the marginal likelihood as a direct byproduct of estimation, the algorithm is an alternative to Markov chain Monte Carlo techniques also in batch estimation settings.

---

##### Figure 5

![](paper11.png)

---

##### Citation

Sørensen, Ø., Stein, A., Netto, W. L., & Leslie, D. S. (2024). Sequential Rank and Preference Learning with the Bayesian Mallows Model (No. arXiv:2412.13644). arXiv. https://doi.org/10.48550/arXiv.2412.13644



```BibTeX
@misc{sorensenSequentialRankPreference2024,
  title = {Sequential {{Rank}} and {{Preference Learning}} with the {{Bayesian Mallows Model}}},
  author = {S{\o}rensen, {\O}ystein and Stein, Anja and Netto, Waldir Leoncio and Leslie, David S.},
  year = {2024},
  month = dec,
  number = {arXiv:2412.13644},
  primaryclass = {stat},
  publisher = {arXiv},
  doi = {10.48550/arXiv.2412.13644},
  archiveprefix = {arXiv},
  keywords = {Statistics - Computation}
}
```

---

##### Related material

+ [R package implementing the methods](https://github.com/osorensen/BayesMallowsSMC2)

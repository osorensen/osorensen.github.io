---
title: "Modeling Cycles, Trends and Time-Varying Effects in Dynamic Structural Equation Models with Regression Splines" 
date: 2025-01-01
lastmod: 2024-07-12
tags: ["DSEM","intensive longitudinal data", "regression splines", "smoothing", "Stan"]
author: [
    "Øystein Sørensen",
    "Ethan M. McCormick"
]
description: "This paper considers rank and preference modeling for the case in which data arrive sequentially, rather than in a batch. The goal is to compute the posterior distribution incrementally in time, so that it can be quickly updated when new data arrives. To this end, we develop a sequential Monte Carlo algorithm for the Bayesian Mallows model. arXiv preprint currently under revision."
summary: "Dynamic structural equation models have become extremely popular for analysis of intensive longitudinal data in the social sciences. One outstanding problem is how to handle nonlinear trends and cycles, and in this paper we propose to do this in a very flexible manner using regression splines. We test the methods in simulation studies, and then illustrate them by analyzing a diary data set on alcohol consumption and stress. Open-source Stan code is available from our OSF repository. Accepted for publication in Multivariate Behavioral Research."
cover:
    image: "paper12.png"
    
    relative: false
editPost:
    URL: "https://doi.org/10.48550/arXiv.2412.13644"
    Text: "Accepted for publication in Multivariate Behavioral Research"

---

---

##### Download

+ [Paper](https://doi.org/10.31234/osf.io/2ajpt)
+ [Stan code](https://osf.io/qpkmg/)

---

##### Abstract

Intensive longitudinal data with a large number of timepoints per individual are becoming increasingly common. Such data allow going beyond the classical growth model situation and studying population effects and individual variability not only in trends over time but also in autoregressive effects, cross-lagged effects, and the noise term. Dynamic structural equation models (DSEMs) have become very popular for analyzing intensive longitudinal data. However, when the data contain trends, cycles, or time-varying predictors which have nonlinear effects on the outcome, DSEMs require the practitioner to specify the correct parametric form of the effects, which may be challenging in practice. In this paper we show how to alleviate this issue by introducing regression splines which are able to flexibly learn the underlying function shapes. Our main contribution is thus a building block to the DSEM modeler's toolkit, and we discuss smoothing priors and hierarchical smooth terms using the special cases of two-level lag-1 autoregressive and vector autoregressive models as examples. We illustrate in simulation studies how ignoring nonlinear trends may lead to biased parameter estimates, and then show how to use the proposed framework to model weekly cycles and long-term trends in diary data on alcohol consumption and perceived stress.

---

##### Figure 4

![](paper12.png)

---

##### Citation

Sørensen, Ø., & McCormick, E. M. (2025). Modeling Cycles, Trends and Time-Varying Effects in Dynamic Structural Equation Models with Regression Splines. OSF. https://doi.org/10.31234/osf.io/2ajpt




```BibTeX
@misc{sorensenModelingCyclesTrends2025,
  title = {Modeling {{Cycles}}, {{Trends}} and {{Time-Varying Effects}} in {{Dynamic Structural Equation Models}} with {{Regression Splines}}},
  author = {S{\o}rensen, {\O}ystein and McCormick, Ethan M.},
  year = {2025},
  month = jan,
  publisher = {OSF},
  doi = {10.31234/osf.io/2ajpt},
  archiveprefix = {OSF},
  langid = {american},
  keywords = {DSEM,intensive longitudinal data,regression splines,smoothing,Stan.}
}
```


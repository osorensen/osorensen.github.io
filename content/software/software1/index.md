---
title: "galamm - Generalized Additive Latent and Mixed Models" 
date: 2023-09-01
lastmod: 2024-05-08
tags: ["galamm","R","generalized additive latent and mixed models"]
author: ["Øystein Sørensen"]
description: "This R package contains functions for estimating generalized additive latent and mixed models."
summary: "This R package contains functions for estimating generalized additive latent and mixed models."
editPost:
    URL: "https://cran.r-project.org/package=galamm"
    Text: "R package on CRAN"
showToc: false
disableAnchoredHeadings: false

---


#### Description

Estimates generalized additive latent and mixed models using maximum marginal likelihood, as defined in Sorensen et al. (2023) <doi:10.1007/s11336-023-09910-z>, which is an extension of Rabe-Hesketh and Skrondal (2004)'s unifying framework for multilevel latent variable modeling <doi:10.1007/BF02295939>. Efficient computation is done using sparse matrix methods, Laplace approximation, and automatic differentiation. The framework includes generalized multilevel models with heteroscedastic residuals, mixed response types, factor loadings, smoothing splines, crossed random effects, and combinations thereof. Syntax for model formulation is close to 'lme4' (Bates et al. (2015) <doi:10.18637/jss.v067.i01>) and 'PLmixed' (Rockwood and Jeon (2019) <doi:10.1080/00273171.2018.1516541>).


---

#### Background

For more background, see the [original paper on GALAMM](../../papers/paper9) and the [software paper](../../papers/paper10).
---
title: "hdme: High-Dimensional Regression with Measurement Error" 
date: 2018-03-01
lastmod: 2024-05-08
tags: ["hdme","R","measurement error", "lasso", "matrix uncertainty selector", "Dantzig selector"]
author: ["Øystein Sørensen"]
description: "This R package contains functions for fitting variable selection models in the presence of noise in the predictor variables. In particular, it supports a corrected lasso and the generalized matrix uncertainty selector. In addition, it offers an implementation of the (generalized) Dantzig selector."
summary: "This R package contains functions for fitting variable selection models in the presence of noise in the predictor variables. In particular, it supports a corrected lasso and the generalized matrix uncertainty selector. In addition, it offers an implementation of the (generalized) Dantzig selector."
editPost:
    URL: "https://cran.r-project.org/package=hdme"
    Text: "R package on CRAN"
showToc: false
disableAnchoredHeadings: false

---


#### Description

Penalized regression for generalized linear models for measurement error problems (aka. errors-in-variables). The package contains a version of the lasso (L1-penalization) which corrects for measurement error (Sorensen et al. (2015) <doi:10.5705/ss.2013.180>). It also contains an implementation of the Generalized Matrix Uncertainty Selector, which is a version the (Generalized) Dantzig Selector for the case of measurement error (Sorensen et al. (2018) <doi:10.1080/10618600.2018.1425626>).


---

#### Background

For more background, see the [paper on measurement error in lasso](../../papers/paper1) and the [paper on the generalized matrix uncertainty selector](../../papers/paper2).
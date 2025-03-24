---
title: "metagam: Meta-Analysis of Generalized Additive Models" 
date: 2020-02-01
lastmod: 2024-05-08
tags: ["metagam","R","generalized additive models", "meta analysis"]
author: ["Øystein Sørensen"]
description: "This R package contains functions for meta analysis using generalized additive (mixed) models, by combining fits from multiple studies."
summary: "This R package contains functions for meta analysis using generalized additive (mixed) models, by combining fits from multiple studies."
editPost:
    URL: "https://cran.r-project.org/package=metagam"
    Text: "R package on CRAN"
showToc: false
disableAnchoredHeadings: false

---


#### Description

Meta-analysis of generalized additive models and generalized additive mixed models. A typical use case is when data cannot be shared across locations, and an overall meta-analytic fit is sought. 'metagam' provides functionality for removing individual participant data from models computed using the 'mgcv' and 'gamm4' packages such that the model objects can be shared without exposing individual data. Furthermore, methods for meta-analysing these fits are provided. The implemented methods are described in Sorensen et al. (2020), <doi:10.1016/j.neuroimage.2020.117416>, extending previous works by Schwartz and Zanobetti (2000) and Crippa et al. (2018) <doi:10.6000/1929-6029.2018.07.02.1>.


---

#### Background

For more background, see the [original paper on the method](../../papers/paper7).
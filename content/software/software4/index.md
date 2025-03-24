---
title: "BayesianLaterality - Predict Brain Asymmetry Based on Handedness and Dichotic Listening" 
date: 2020-09-01
lastmod: 2024-05-08
tags: ["BayesianLaterality","R","dichotic listening", "brain asymmetry"]
author: ["Øystein Sørensen"]
description: "This R package contains functions for estimating whether a subject is left- or right-dominant for language processing based on the results of dichotic listening experiments and information about handedness."
summary: "This R package contains functions for estimating whether a subject is left- or right-dominant for language processing based on the results of dichotic listening experiments and information about handedness."
editPost:
    URL: "https://cran.r-project.org/package=BayesianLaterality"
    Text: "R package on CRAN"
showToc: false
disableAnchoredHeadings: false

---


#### Description

Functional differences between the cerebral hemispheres are a fundamental characteristic of the human brain. Researchers interested in studying these differences often infer underlying hemispheric dominance for a certain function (e.g., language) from laterality indices calculated from observed performance or brain activation measures . However, any inference from observed measures to latent (unobserved) classes has to consider the prior probability of class membership in the population. The provided functions implement a Bayesian model for predicting hemispheric dominance from observed laterality indices (Sorensen and Westerhausen, Laterality: Asymmetries of Body, Brain and Cognition, 2020, <doi:10.1080/1357650X.2020.1769124>).


---

#### Background

For more background, see the [original paper on the method](../../papers/paper6).
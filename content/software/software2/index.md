---
title: "BayesMallows: Bayesian Preference Learning with the Mallows Rank Model" 
date: 2018-10-01
lastmod: 2024-05-08
tags: ["Mallows model","R","BayesMallows", "rankings", "preferences"]
author: ["Øystein Sørensen", "Waldir Leoncio Netto", "Valeria Vitelli", "Marta Crispino", "et al."]
description: "This R package contains functions for estimating the Bayesian Mallows model in a wide range of situation, using the Metropolis-Hastings algorithm."
summary: "This R package contains functions for estimating the Bayesian Mallows model in a wide range of situation, using the Metropolis-Hastings algorithm."
editPost:
    URL: "https://cran.r-project.org/package=BayesMallows"
    Text: "R package on CRAN"
showToc: false
disableAnchoredHeadings: false

---


#### Description

An implementation of the Bayesian version of the Mallows rank model (Vitelli et al., Journal of Machine Learning Research, 2018 <https://jmlr.org/papers/v18/15-481.html>; Crispino et al., Annals of Applied Statistics, 2019 <doi:10.1214/18-AOAS1203>; Sorensen et al., R Journal, 2020 <doi:10.32614/RJ-2020-026>; Stein, PhD Thesis, 2023 <https://eprints.lancs.ac.uk/id/eprint/195759>). Both Metropolis-Hastings and sequential Monte Carlo algorithms for estimating the models are available. Cayley, footrule, Hamming, Kendall, Spearman, and Ulam distances are supported in the models. The rank data to be analyzed can be in the form of complete rankings, top-k rankings, partially missing rankings, as well as consistent and inconsistent pairwise preferences. Several functions for plotting and studying the posterior distributions of parameters are provided. The package also provides functions for estimating the partition function (normalizing constant) of the Mallows rank model, both with the importance sampling algorithm of Vitelli et al. and asymptotic approximation with the IPFP algorithm (Mukherjee, Annals of Statistics, 2016 <doi:10.1214/15-AOS1389>).


---

#### Background

For more background, see the [original paper on the Bayesian Mallows model](../../papers/paper3) and the [software paper](../../papers/paper5).
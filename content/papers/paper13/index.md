---
title: "Gaining Brain Insights by Tapping into the Black Box: Linking Structural MRI Features to Age and Cognition using Shapley-Based Interpretation Methods" 
date: 2025-10-22
lastmod: 2025-10-22
tags: ["explainable AI","SHAP", "neuroimaging", "brain aging", "machine learning", "XGBoost"]
author: [
    "Julia Kropiunig",
    "Øystein Sørensen"
]
description: "This paper evaluates multiple interpretability techniques for machine learning models applied to neuroimaging data, including SHAP and SAGE. We trained XGBoost models to predict age and fluid intelligence using UK Biobank data and found that subcortical mean intensities are associated with brain aging, while fluid intelligence prediction is driven by the hippocampus and cerebellum. Published in Neuroinformatics."
summary: "This paper evaluates multiple interpretability techniques for machine learning models applied to neuroimaging data, including SHAP and SAGE. We trained XGBoost models to predict age and fluid intelligence using UK Biobank data and found that subcortical mean intensities are associated with brain aging, while fluid intelligence prediction is driven by the hippocampus and cerebellum. Published in Neuroinformatics."
cover:
    image: ""
    
    relative: false
editPost:
    URL: "https://doi.org/10.1007/s12021-025-09737-2"
    Text: "Neuroinformatics"

---

---

##### Download

+ [Paper](https://doi.org/10.1007/s12021-025-09737-2)
+ [Code and simulated data](https://osf.io/epmgk/)

---

##### Abstract

Global interpretability in machine learning holds great potential for extracting meaningful insights from neuroimaging data to improve our understanding of brain function. Although various approaches exist to identify key contributing features at both local and global levels, the high dimensionality and correlations in neuroimaging data require careful selection of interpretability methods to achieve reliable global insights into brain function using machine learning. In this study, we evaluate multiple interpretability techniques such as SHAP, which relies on feature independence, as well as recent advances that account for feature dependence in the context of global interpretability, and inherently global methods such as SAGE. To demonstrate the practical application, we trained XGBoost models to predict age and fluid intelligence using neuroimaging measures from the UK Biobank dataset. By applying these interpretability methods, we found that mean intensities in subcortical regions are consistently and significantly associated with brain aging, while the prediction of fluid intelligence is driven by contributions of the hippocampus and the cerebellum, alongside established regions such as the frontal and temporal lobes. These results underscore the value of interpretable machine learning methods in understanding brain function through a data-driven approach.

---

##### Citation

Kropiunig, J., & Sørensen, Ø. (2025). Gaining Brain Insights by Tapping into the Black Box: Linking Structural MRI Features to Age and Cognition using Shapley-Based Interpretation Methods. Neuroinformatics, 23, 52. https://doi.org/10.1007/s12021-025-09737-2



```BibTeX
@article{Kropiunig2025,
  title = {Gaining Brain Insights by Tapping into the Black Box: Linking Structural MRI Features to Age and Cognition using Shapley-Based Interpretation Methods},
  author = {Kropiunig, Julia and S{\o}rensen, {\O}ystein},
  journal = {Neuroinformatics},
  volume = {23},
  pages = {52},
  year = {2025},
  publisher = {Springer},
  doi = {10.1007/s12021-025-09737-2},
  URL = {https://doi.org/10.1007/s12021-025-09737-2}
}
```


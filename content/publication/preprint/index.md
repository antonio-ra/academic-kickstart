---
title: "Marginalization of Regression-Adjusted Treatment Effects in Indirect Comparisons with Limited Patient-Level Data"
authors:
- admin
- Anna Heath
- Gianluca Baio
date: "2019-04-07T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2008.05951"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

abstract: 

Population adjustment methods such as matching-adjusted indirect comparison (MAIC) are increasingly used to compare marginal treatment effects when there are cross-trial differences in effect modifiers and limited patient-level data. MAIC is sensitive to poor covariate overlap and cannot extrapolate beyond the observed covariate space. Current outcome regression-based alternatives can extrapolate but target a conditional treatment effect that is incompatible in the indirect comparison. When adjusting for covariates, one must integrate or average the conditional estimate over the population of interest to recover a compatible marginal treatment effect. We propose a marginalization method based on parametric G-computation that can be easily applied where the outcome regression is a generalized linear model or a Cox model. In addition, we introduce a novel general-purpose method based on multiple imputation, which we term multiple imputation marginalization (MIM) and is applicable to a wide range of models. Both methods can accommodate a Bayesian statistical framework, which naturally integrates the analysis into a probabilistic framework. A simulation study provides proof-of-principle for the methods and benchmarks their performance against MAIC and the conventional outcome regression. The marginalized outcome regression approaches achieve more precise and more accurate estimates than MAIC, particularly when covariate overlap is poor, and yield unbiased marginal treatment effect estimates under no failures of assumptions. Furthermore, the marginalized regression-adjusted estimates provide greater precision and accuracy than the conditional estimates produced by the conventional outcome regression, which are systematically biased because the measure of effect is non-collapsible.

featured: false

links:
url_pdf: https://arxiv.org/pdf/2008.05951
url_code: 'https://github.com/remiroazocar/marginalized_indirect_comparisons_simstudy'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'
---

This work ultimately evolved into two peer-reviewed publications, on [parametric G-computation in the context of indirect treatment comparisons](https://doi.org/10.1002/jrsm.1565) and [multiple imputation marginalization](https://doi.org/10.1186/s12874-024-02157-x).

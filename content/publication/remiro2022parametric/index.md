---
title: "Parametric G-computation for compatible indirect treatment comparisons with limited individual patient data"
authors:
- admin
- Anna Heath
- Gianluca Baio
date: "2022-04-29T00:00:00Z"
doi: "https://doi.org/10.1002/jrsm.1565"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Research Synthesis Methods, 13*(6)"
publication_short: ""

abstract: Population adjustment methods such as matching-adjusted indirect comparison (MAIC) are increasingly used to compare marginal treatment effects when there are cross-trial differences in effect modifiers and limited patient-level data. MAIC is based on propensity score weighting, which is sensitive to poor covariate overlap and cannot extrapolate beyond the observed covariate space. Current outcome regression-based alternatives can extrapolate but target a conditional treatment effect that is incompatible in the indirect comparison. When adjusting for covariates, one must integrate or average the conditional estimate over the relevant population to recover a compatible marginal treatment effect. We propose a marginalization method based on parametric G-computation that can be easily applied where the outcome regression is a generalized linear model or a Cox model. The approach views the covariate adjustment regression as a nuisance model and separates its estimation from the evaluation of the marginal treatment effect of interest. The method can accommodate a Bayesian statistical framework, which naturally integrates the analysis into a probabilistic framework. A simulation study provides proof-of-principle and benchmarks the method's performance against MAIC and the conventional outcome regression. Parametric G-computation achieves more precise and more accurate estimates than MAIC, particularly when covariate overlap is poor, and yields unbiased marginal treatment effect estimates under no failures of assumptions. Furthermore, the marginalized regression-adjusted estimates provide greater precision and accuracy than the conditional estimates produced by the conventional outcome regression, which are systematically biased because the measure of effect is non-collapsible.

tags:
- Research Synthesis Methods
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2108.12208
url_code: 'https://github.com/remiroazocar/Gcomp_indirect_comparisons_simstudy'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
---

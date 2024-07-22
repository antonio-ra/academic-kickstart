---
title: "Model-based standardization using multiple imputation"
authors:
- admin
- Anna Heath
- Gianluca Baio
date: "2024-02-10T00:00:00Z"
doi: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*BMC Medical Research Methodology, 24*(1)"
publication_short: ""

abstract: When studying the association between treatment and a clinical outcome, a parametric multivariable model of the conditional outcome expectation is often used to adjust for covariates. The treatment coefficient of the outcome model targets a conditional treatment effect. Model-based standardization is typically applied to average the model predictions over the target covariate distribution, and generate a covariate-adjusted estimate of the marginal treatment effect. The standard approach to model-based standardization involves maximum-likelihood estimation and use of the non-parametric bootstrap. We introduce a novel, general-purpose, model-based standardization method based on multiple imputation that is easily applicable when the outcome model is a generalized linear model. We term our proposed approach multiple imputation marginalization (MIM). MIM consists of two main stages - the generation of synthetic datasets and their analysis. MIM accommodates a Bayesian statistical framework, which naturally allows for the principled propagation of uncertainty, integrates the analysis into a probabilistic framework, and allows for the incorporation of prior evidence. We conduct a simulation study to benchmark the finite-sample performance of MIM in conjunction with a parametric outcome model. The simulations provide proof-of-principle in scenarios with binary outcomes, continuous-valued covariates, a logistic outcome model and the marginal log odds ratio as the target effect measure. When parametric modeling assumptions hold, MIM yields unbiased estimation in the target covariate distribution, valid coverage rates, and similar precision and efficiency than the standard approach to model-based standardization. We demonstrate that multiple imputation can be used to marginalize over a target covariate distribution, providing appropriate inference with a correctly specified parametric outcome model and offering statistical performance comparable to that of the standard approach to model-based standardization.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2305.08284
url_code: 'https://github.com/remiroazocar/MIM'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

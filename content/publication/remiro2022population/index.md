---
title: "Population-adjusted indirect treatment comparisons with limited access to patient-level data"
authors:
- admin
date: "2022-03-28T00:00:00Z"
doi: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: "*Doctoral dissertation, UCL (University College London))*"
publication_short: ""

abstract: Health technology assessment systems base their decision-making on health-economic evaluations. These require accurate relative treatment effect estimates for specific patient populations. In an ideal scenario, a head-to-head randomized controlled trial, directly comparing the interventions of interest, would be available. Indirect treatment comparisons are necessary to contrast treatments which have not been analyzed in the same trial. Population-adjusted indirect comparisons estimate treatment effects where there are no head-to-head trials between the interventions of interest, limited access to patient-level data, and cross-trial differences in effect measure modifiers. Health technology assessment agencies are increasingly accepting evaluations that use these methods across a diverse range of therapeutic areas. Popular approaches include matching-adjusted indirect comparison (MAIC), based on propensity score weighting, and simulated treatment comparison (STC), based on outcome regression. There is limited formal evaluation of these methods and whether they can be used to accurately compare treatments. Thus, I undertake a review and a simulation study that compares the standard unadjusted indirect comparisons, MAIC and STC across 162 scenarios. This simulation study assumes that the trials are investigating survival outcomes and measure continuous covariates, with the log hazard ratio as the measure of effect — one of the most widely used setups in health technology assessment applications. MAIC yields unbiased treatment effect estimates under no failures of assumptions. The typical usage of STC produces bias because it targets a conditional treatment effect where the target estimand should be a marginal treatment effect. The incompatibility of estimates in the indirect comparison leads to bias as the measure of effect is non-collapsible. When adjusting for covariates, one must integrate or average the conditional model over the population of interest to recover a compatible marginal treatment effect. I propose a marginalization method based on parametric G-computation that can be easily applied where the outcome regression is a generalized linear model or a Cox model. In addition, I introduce a novel general-purpose method based on the ideas underlying multiple imputation, which is termed multiple imputation marginalization (MIM) and is applicable to a wide range of models, including parametric survival models. The approaches view the covariate adjustment regression as a nuisance model and separate its estimation from the evaluation of the marginal treatment effect of interest. Both methods can accommodate a Bayesian statistical framework, which naturally integrates the analysis into a probabilistic framework, typically required for health technology assessment. Another simulation study provides proof-of-principle for the methods and benchmarks their performance against MAIC and the conventional STC. The simulations are based on scenarios with binary outcomes and continuous covariates, with the log-odds ratio as the measure of effect. The marginalized outcome regression approaches achieve more precise and more accurate estimates than MAIC, particularly when covariate overlap is poor, and yield unbiased marginal treatment effect estimates under no failures of assumptions. Furthermore, regression-adjusted estimates of the marginal effect provide greater precision and accuracy than the conditional estimates produced by the conventional STC, which are systematically biased because the log-odds ratio is a non-collapsible measure of effect. The marginalization methods outlined in this thesis are necessary and important for health technology assessment more generally, because marginal treatment effects should be the preferred inferential target for reimbursement decisions at the population level. Treatment effectiveness inputs in health economic models are often informed by the treatment coefficient of a multivariable regression. An often overlooked issue is that this has a conditional interpretation, and that the coefficients of the regression must be marginalized over the target population of interest to produce a relevant estimate for reimbursement decisions at the population level.

tags:
- Doctoral Thesis
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://discovery.ucl.ac.uk/id/eprint/10144848/1/Remiro%20Azocar__thesis_redacted_final.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

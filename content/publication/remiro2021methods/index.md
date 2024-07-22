---
title: "Methods for population adjustment with limited access to individual patient data - A review and simulation study"
authors:
- admin
- Anna Heath
- Gianluca Baio
date: "2024-06-30T00:00:00Z"
doi: "https://doi.org/10.1002/jrsm.1511"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Research Synthesis Methods, 12*(6)"
publication_short: ""

abstract: Population-adjusted indirect comparisons estimate treatment effects when access to individual patient data is limited and there are cross-trial differences in effect modifiers. Popular methods include matching-adjusted indirect comparison (MAIC) and simulated treatment comparison (STC). There is limited formal evaluation of these methods and whether they can be used to accurately compare treatments. Thus, we undertake a comprehensive simulation study to compare standard unadjusted indirect comparisons, MAIC and STC across 162 scenarios. This simulation study assumes that the trials are investigating survival outcomes and measure continuous covariates, with the log hazard ratio as the measure of effect. MAIC yields unbiased treatment effect estimates under no failures of assumptions. The typical usage of STC produces bias because it targets a conditional treatment effect where the target estimand should be a marginal treatment effect. The incompatibility of estimates in the indirect comparison leads to bias as the measure of effect is non-collapsible. Standard indirect comparisons are systematically biased, particularly under stronger covariate imbalance and interaction effects. Standard errors and coverage rates are often valid in MAIC but the robust sandwich variance estimator underestimates variability where effective sample sizes are small. Interval estimates for the standard indirect comparison are too narrow and STC suffers from bias-induced undercoverage. MAIC provides the most accurate estimates and, with lower degrees of covariate overlap, its bias reduction outweighs the loss in precision under no failures of assumptions. An important future objective is the development of an alternative formulation to STC that targets a marginal treatment effect.

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2004.14800
url_code: 'https://github.com/remiroazocar/population_adjustment_simstudy'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

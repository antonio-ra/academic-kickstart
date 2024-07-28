---
title: "Two-stage matching-adjusted indirect comparison"
authors:
- admin
date: "2022-08-08T00:00:00Z"
doi: "https://doi.org/10.1186/s12874-022-01692-9"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*BMC Medical Research Methodology, 22*(1)"
publication_short: ""

abstract: Anchored covariate-adjusted indirect comparisons inform reimbursement decisions where there are no head-to-head trials between the treatments of interest, there is a common comparator arm shared by the studies, and there are patient-level data limitations. Matching-adjusted indirect comparison (MAIC), based on propensity score weighting, is the most widely used covariate-adjusted indirect comparison method in health technology assessment. MAIC has poor precision and is inefficient when the effective sample size after weighting is small. A modular extension to MAIC, termed two-stage matching-adjusted indirect comparison (2SMAIC), is proposed. This uses two parametric models. One estimates the treatment assignment mechanism in the study with individual patient data (IPD), the other estimates the trial assignment mechanism. The first model produces inverse probability weights that are combined with the odds weights produced by the second model. The resulting weights seek to balance covariates between treatment arms and across studies. A simulation study provides proof-of-principle in an indirect comparison performed across two randomized trials. Nevertheless, 2SMAIC can be applied in situations where the IPD trial is observational, by including potential confounders in the treatment assignment model. The simulation study also explores the use of weight truncation in combination with MAIC for the first time. Despite enforcing randomization and knowing the true treatment assignment mechanism in the IPD trial, 2SMAIC yields improved precision and efficiency with respect to MAIC in all scenarios, while maintaining similarly low levels of bias. The two-stage approach is effective when sample sizes in the IPD trial are low, as it controls for chance imbalances in prognostic baseline covariates between study arms. It is not as effective when overlap between the trials’ target populations is poor and the extremity of the weights is high. In these scenarios, truncation leads to substantial precision and efficiency gains but induces considerable bias. The combination of a two-stage approach with truncation produces the highest precision and efficiency improvements. Two-stage approaches to MAIC can increase precision and efficiency with respect to the standard approach by adjusting for empirical imbalances in prognostic covariates in the IPD trial. Further modules could be incorporated for additional variance reduction or to account for missingness and non-compliance in the IPD trial.

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2204.11325
url_code: 'https://github.com/remiroazocar/Maic2stage'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

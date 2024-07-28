---
title: "Effect modification in anchored indirect treatment comparison - Comments on “Matching-adjusted indirect comparisons - Application to time-to-event data”"
authors:
- admin
- Anna Heath
- Gianluca Baio
date: "2022-03-11T00:00:00Z"
doi: "https://doi.org/10.1002/sim.9286"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Statistics in Medicine, 41*(8)"
publication_short: ""

abstract: This commentary regards a recent simulation study conducted by Aouni, Gaudel-Dedieu and Sebastien, evaluating the performance of different versions of matching-adjusted indirect comparison (MAIC) in an anchored scenario with a common comparator. The simulation study uses survival outcomes and the Cox proportional hazards regression as the outcome model. It concludes that using the LASSO for variable selection is preferable to balancing a maximal set of covariates. However, there are no treatment effect modifiers in imbalance in the study. The LASSO is more efficient because it selects a subset of the maximal set of covariates but there are no cross-study imbalances in effect modifiers inducing bias. We highlight that (1) in the anchored setting, MAIC is necessary where there are cross-trial imbalances in effect modifiers; (2) the standard indirect comparison provides greater precision and accuracy than MAIC if there are no effect modifiers in imbalance; (3) while the target estimand of the simulation study is a conditional treatment effect, MAIC targets a marginal or population-average treatment effect; (4) in MAIC, variable selection is a problem of low dimensionality and sparsity-inducing methods like the LASSO may be problematic. Finally, data-driven approaches do not obviate the necessity for subject matter knowledge when selecting effect modifiers. R code is provided in the Appendix to replicate the analyses and illustrate our points.

tags:
- Statistics in Medicine
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/2012.05127
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---

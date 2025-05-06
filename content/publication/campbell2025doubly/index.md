---
title: "Doubly robust augmented weighting estimators for the analysis of externally controlled single-arm trials and unanchored indirect treatment comparisons"
authors:
- Harlan Campbell
- admin
date: "2025-04-30T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2505.00113"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

abstract: Externally controlled single-arm trials are critical to assess treatment efficacy across therapeutic indications for which randomized controlled trials are not feasible. A closely-related research design, the unanchored indirect treatment comparison, is often required for disconnected treatment networks in health technology assessment. We present a unified causal inference framework for both research designs. We develop a novel estimator that augments a popular weighting approach based on entropy balancing - matching-adjusted indirect comparison (MAIC) - by fitting a model for the conditional outcome expectation. The predictions of the outcome model are combined with the entropy balancing MAIC weights. While the standard MAIC estimator is singly robust where the outcome model is non-linear, our augmented MAIC approach is doubly robust, providing increased robustness against model misspecification. This is demonstrated in a simulation study with binary outcomes and a logistic outcome model, where the augmented estimator demonstrates its doubly robust property, while exhibiting higher precision than all non-augmented weighting estimators and near-identical precision to G-computation. We describe the extension of our estimator to the setting with unavailable individual participant data for the external control, illustrating it through an applied example. Our findings reinforce the understanding that entropy balancing-based approaches have desirable properties compared to standard modeling approaches to weighting, but should be augmented to improve protection against bias and guarantee double robustness.

tags:
- Pre-print
featured: true

links:
url_pdf: 'https://arxiv.org/pdf/2505.00113'
url_code: 'https://github.com/harlanhappydog/DRAWE-'
---

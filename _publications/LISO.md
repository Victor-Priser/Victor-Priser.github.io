---
title: "Importance Sampling Optimization with Laplace Principle"
collection: preprint
#category: manuscripts
permalink: /publication/LISO
#excerpt: 'This paper is about the number 3. The number 4 is left for future work.'
date: 2026-03-01
venue: 'preprint'
#slidesurl: 'https://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://arxiv.org/pdf/2604.02882'
citation: 'Dragomir R.-A., Portier F., Priser V.'
---



Grid search and random search are widely used techniques for hyperparameter tuning in
machine learning, especially when gradient information is unavailable. In these methods, a
finite set of candidate configurations is evaluated, and the best-performing one is selected.
We propose a simple and computationally inexpensive refinement of this paradigm: instead
of selecting a single best point, we form a weighted average of the evaluated configurations,
where the weights are chosen using an importance sampling scheme inspired by the Laplace
principle. This scheme can be implemented as a post-processing step on top of a random
search, with no additional function evaluations. We also propose an iterative variant, where
the sampling distributions are chosen adaptively to generate new candidate points around the
previous estimate, in the spirit of Evolution Strategy (ES) methods.
In a general non-convex setting, we show that, after n evaluations, the error of the proposed
methods is of smaller order than n^{-2/(d+2)}. This compares favorably to random search or grid
search rates of n^{−1/d} as soon as d > 2. We illustrate the practical benefits of this averaging
strategy on several examples.

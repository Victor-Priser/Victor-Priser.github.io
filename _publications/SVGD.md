---
title: "Long-time asymptotics of noisy SVGD outside the population limit"
collection: publications
#category: manuscripts
permalink: /publication/SVGD
# excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
date: 2024-06-01
venue: 'ICLR'
paperurl: 'https://openreview.net/pdf?id=X7eAhXcps1'
citation: 'Bianchi P., Priser V., Salim A.'
---
Stein Variational Gradient Descent (SVGD) is a widely used sampling algorithm that has been successfully applied in several areas of Machine Learning. SVGD operates by iteratively moving a set of *n* interacting particles (which represent the samples) to approximate the target distribution. 

Despite recent studies on the complexity of SVGD and its variants, their long-time asymptotic behavior (i.e., after numerous iterations *k*) is still not understood in the finite number of particles regime. 

We study the long-time asymptotic behavior of a noisy variant of SVGD. First, we establish that the limit set of noisy SVGD for large *k* is well-defined. We then characterize this limit set, showing that it approaches the target distribution as *n* increases. In particular, noisy SVGD avoids the variance collapse observed for SVGD. 

Our approach involves demonstrating that the trajectories of noisy SVGD closely resemble those described by a McKean-Vlasov process.

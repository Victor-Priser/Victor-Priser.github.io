---
title: "Stochastic mirror descent for nonparametric adaptive importance sampling"
collection: preprint
#category: conferences
permalink: /publication/MIDAS
#excerpt: 'This paper is about fixing template issue #693.'
date: 2024-09-01
venue: 'preprint'
paperurl: 'https://www.arxiv.org/pdf/2409.13272'
citation: 'Bianchi P., Delyon B., Priser V., Portier F.'
---

This paper addresses the problem of approximating an unknown probability distribution with density f — which can only be evaluated up to an unknown scaling factor — with the help of a sequential algorithm that produces at each iteration n \geq 1 an estimated density q_n.

The proposed method optimizes the Kullback-Leibler divergence using a mirror descent (MD) algorithm directly on the space of density functions, while a stochastic approximation technique helps to balance algorithm complexity and variability. One of the key innovations of this work is the theoretical guarantee provided for an algorithm with a fixed MD learning rate $0<\eta <1$.


The main result is that the sequence $q_n$ converges almost surely to the target density $f$ uniformly on compact sets. Through numerical experiments, we show that fixing the learning rate $\eta \in (0,1)$ significantly improves the algorithm's performance, particularly in the context of multi-modal target distributions, where a small value of $\eta$ increases the chance of finding all modes. 

Additionally, we propose a particle subsampling method to enhance computational efficiency and compare our method against other approaches through numerical experiments.

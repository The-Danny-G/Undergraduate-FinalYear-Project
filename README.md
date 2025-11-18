# Estimating Parameters of Truncated Distributions using Likelihood-Free Simulation-Based Methods.

This is the full pdf of my final undergraduate project submission in 2023. 

## Abstract

In this paper we consider methods of statistical inference where the
likelihood function of a model is not directly tractable but still able to
be sampled from. We look at cases where this density is intractable due
to having a normalising constant that cannot be analytically calculated
due to being integrated over a complex truncated domain. We first in-
vestigate two well known non-likelihood estimation methods: indirect
inference and approximate Bayesian computation (ABC), then go on
to introduce the maximum mean discrepancy (MMD) as a distance to
use for parameter estimation.

We then go on to look at ways of simulating a truncated normal distri-
bution given different truncation domains, and several different ways
of optimising the MMD distance function, which we will show contains
a lot of deterministic noise. Finally we end by analysing the MMD
estimator’s performance in different scenarios, and comparing it to the
two initial non-likelihood estimation methods in the context of trun-
cated domains. We conclude that the MMD estimator is more effective
than conventional methods such as basic ABC in these contexts.

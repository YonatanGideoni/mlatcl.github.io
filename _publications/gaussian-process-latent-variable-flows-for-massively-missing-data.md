---
layout: publication-single
title: Gaussian Process Latent Variable Flows for Massively Missing Data
author: "Lalchand, V., Ravuri, A. and Lawrence, ND. (2021) "
references: Third Symposium on Advances in Approximate Bayesian Inference
---
Gaussian process latent variable models (GPLVM) are used to perform nonlinear and probabilistic dimensionality reduction. They extend Gaussian processes (GP) to the domain of unsupervised learning. The Bayesian incarnation of the GPLVM uses a variational framework, where the posterior over all unknown quantities is approximated by a well-behaved variational family, a factorised Gaussian. This gives not only implicit regularisation but also mathematical convenience. In this work we narrow our focus on examining the quality of the latent representation learnt under this Gaussian assumption. We introduce non-Gaussianity in the distribution of the latent space through normalising flows. The flexibility afforded by flows is critical in modelling massively missing data. Inference is performed using Stochastic Variational Inference (SVI) with a structured variational lower bound that factorizes across data points permitting efficient and scalable mini-batching of gradients. We call this flexible model class (GPLVF). We compare this framework with traditional models like the Bayesian GPLVM. Our experiments focus on massively missing data settings.

For the full paper, please [visit this link.](https://openreview.net/forum?id=zaMwvOjsyym)
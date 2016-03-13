## KScorrect R package for Lilliefors-corrected Kolmogorov-Smirnoff
goodness-of-fit tests

KScorrect implements the Lilliefors-corrected Kolmogorov-Smirnoff test for use 
in goodness-of-fit tests, suitable when population parameters are unknown and 
must be estimated by sample statistics. P-values are estimated by simulation.
Coded to complement stats::ks.test, it can be used with a variety of continuous
distributions, including normal, lognormal, mixture of normals, uniform,
loguniform, exponential, gamma, and Weibull distributions.

Functions are also provided to generate random numbers and calculate density, 
distribution, and quantile functions for the loguniform and normal mixture 
distributions.

The most recent commit is currently: [![Travis-CI Build 
Status](https://travis-ci.org/pnovack-gottshall/KScorrect.svg?branch=master)](https://travis-ci.org/pnovack-gottshall/KScorrect)
(Travis CI)

This package is authored by Phil Novack-Gottshall 
(<mailto:pnovack-gottshall@ben.edu>) and Steve C. Wang 
(<mailto:scwang@swarthmore.edu>) and offered under CC0.

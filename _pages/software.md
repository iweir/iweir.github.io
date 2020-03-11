---
layout: archive
title: "R packages and functions"
permalink: /software/
author_profile: true
redirect_from:
  - /resume
---


### R packages available on CRAN
- [MetaRMST](https://cran.r-project.org/web/packages/metaRMST/index.html):
R implementation of a multivariate meta-analysis of randomized controlled trials (RCT) with the difference in restricted mean survival times (RMSTD). Use this package with individual patient level data from an RCT for a time-to-event outcome to determine combined effect estimates according to 4 methods: 1) a univariate meta-analysis using observed treatment effects, 2) a univariate meta-analysis using effects predicted by fitted Royston-Parmar flexible parametric models, 3) multivariate meta-analysis with analytically derived covariance, 4) multivariate meta-analysis with bootstrap derived covariance. This package computes all combined effects and provides an RMSTD curve with combined effect estimates and their confidence intervals.

### R functions
- [powerRMST](https://github.com/iweir/powerRMST):
Includes R code for function to determine power under a given sample size using a non-inferiority margin based on the difference in RMST. 
Includes iterative process for determining required sample size in a trial with specified parameters (accrual period, allocation ratio, etc) to achieve a desired target power. 

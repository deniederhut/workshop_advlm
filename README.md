---
title: Advanced Linear Modeling in R
author: Dillon Niederhut
---

[![DOI](https://zenodo.org/badge/doi/10.5281/zenodo.33599.svg)](http://dx.doi.org/10.5281/zenodo.33599)

This repository contains the materials for D-Lab's workshop on linear modeling in R.

## Description:

Linear modeling is the one of the most flexible methods available in inferential statistics, but this flexibility comes at a learning cost. This intermediate workshop in R provides an introduction in and best practices for linear modeling. These includes:

1. Customizing contrasts for factor variables
2. Robusticity against violations of glm assumptions
3. Stepwise regression
4. Heterogeneous model comparison
5. Logistic, Poisson, and other non-Gaussian models

## Requirements:

1. R version >= 3.2.0 installed
2. The following packages installed: 
    - `ggplot2`
    - `lmodel2`
    - `lmtest`
    - `MASS`
    - `reshape2`
    - `robust`

3. Basic familiarity with plotting and the `lm` is assumed

## Contents:

1. data/ -- datafiles necessary for training
2. instructor/ -- instructor materials

## How to Contribute:

If you are an instructor, we encourage you to improve the teaching materials maintained by the D-Lab. We especially encourage you to respond to open issues in this repository. To do so:

1. [Learn how to write in R markdown](http://rmarkdown.rstudio.com/)
2. [Fork this repository](https://help.github.com/articles/fork-a-repo/)
3. Modify your version of these materials
4. Commit and push your changes
5. [Submit a pull request](https://help.github.com/articles/creating-a-pull-request/) with a concise but informative comment about what you have changed
    - if relevant, include in your comment that it `closes #{issue number}`
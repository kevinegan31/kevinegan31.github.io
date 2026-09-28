---
title: "Automatically discovering ordinary differential equations from data with sparse regression"
collection: publications
category: manuscripts
permalink: /publication/2024-commphys-odes
excerpt: 'Developed ARGOS methodology combining denoising techniques, sparse regression, and bootstrap confidence intervals to automatically discover dynamical systems from noisy data.'
date: 2024-01-20
venue: 'Communications Physics'
paperurl: 'https://doi.org/10.1038/s42005-023-01516-2'
# link: 'https://www.nature.com/articles/s42005-023-01516-2'
citation: 'Egan, K., Li, W. & Carvalho, R. (2024). "Automatically discovering ordinary differential equations from data with sparse regression." <i>Communications Physics</i>. 7, 20.'
---

This paper introduces ARGOS, a method for recovering the governing equations of a dynamical system from limited and noisy observations. ARGOS combines denoising, sparse regression, and bootstrap confidence intervals to identify which terms in a candidate equation are supported by the data. Across benchmark systems, it recovered the correct terms more consistently than the widely used SINDy framework and identified how much data, and how little noise, reliable recovery requires.

ARGOS is available as an open-source [R package on CRAN](https://cran.r-project.org/web/packages/ARGOS/index.html).

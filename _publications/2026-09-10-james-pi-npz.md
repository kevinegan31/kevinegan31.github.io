---
title: "Physics-Informed Neural Networks as Differentiable Surrogates for 4D-Variational Data Assimilation"
collection: publications
category: manuscripts
permalink: /publications/2026-09-10-james-pi-npz
excerpt: 'Developed a physics-informed neural surrogate for 4D-Variational Data Assimilation, achieving an approximately six-fold computational speedup while maintaining comparable state-estimation accuracy.'
date: 2026-11-06
venue: 'Journal of Advances in Modeling Earth Systems (JAMES)'
paperurl: 'https://doi.org/10.1029/2025MS005619'
citation: 'Egan, K. & Powell, B. (2026). "Physics-Informed Neural Networks as Differentiable Surrogates for 4D-Variational Data Assimilation." <i>Journal of Advances in Modeling Earth Systems</i>.'
---

This paper introduces a physics-informed machine learning framework for four-dimensional variational data assimilation (4D-Var). The framework unifies the forward, tangent-linear, and adjoint models through automatic differentiation, eliminating the need to separately develop and maintain tangent-linear and adjoint code.

Applied to a nitrate–phytoplankton–zooplankton ecosystem model, the framework achieved an approximately six-fold speedup over traditional numerical models in twin experiments while maintaining comparable state-estimation accuracy across a range of observation sampling scenarios. Analysis of the network's learned sensitivities reveals where embedded ecological relationships agree with the data and where simplified governing equations fall short.

[Read the published article](https://doi.org/10.1029/2025MS005619).

---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computational Engineering, Durham University, 2023
  * Thesis: Automatic Extraction of Ordinary Differential Equations from Data: Sparse Regression Tools for System Identification
* M.S. in Data Science, Northwestern University, 2019
* B.A. in Statistics & Mathematics, Wittenberg University, 2016

Work experience
======
* April 2024 - Present: Postdoctoral Research Scientist
  * University of Hawaiʻi at Mānoa, Honolulu, HI
  * Developed Physics-Informed Neural Network framework for 4D-Variational Data Assimilation achieving 6.5-fold computational speedup over traditional numerical methods
  * Submitted manuscript to Journal of Advances in Modeling Earth Systems
  * Leading CBIOMES–funded workshop on machine learning methods for time-series data (2026)
  * Supervisor: Dr. Brian Powell

* September 2017 - September 2019: Associate Business Analyst
  * Medline Industries, Northfield, IL
  * Reduced rebate inconsistencies by 30% through systematic analysis
  * Established relationships with stakeholders to resolve contract discrepancies

* January 2016 - May 2016: Data and Assessment Assistant
  * Springfield Promise Neighborhood, Springfield, OH
  * Developed logistic regression models and data visualizations for program evaluation
  
Skills
======
* Machine Learning
  * Physics-Informed Neural Networks (PINNs)
  * Automatic differentiation
  * Sparse regression
  * System identification
  * Bayesian hyperparameter optimization
* Data Assimilation & Modeling
  * 4D-Variational Data Assimilation (4D-Var)
  * Numerical methods
  * Dynamical systems
  * Coupled physical-biogeochemical modeling
* Programming & Scientific Computing
  * Python (PyTorch, NumPy, SciPy)
  * R, MATLAB, SQL
  * High-Performance Computing (HPC)
* Languages: Conversational Spanish

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching Experience
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Software Contributions
======
* **ARGOS** (Automatic Regression for Governing Equations): Creator and maintainer of CRAN-published R package for system identification from time-series data
* **PI-NPZ**: Developer of PyTorch-based framework for 4D-Variational Data Assimilation using physics-informed neural networks

Workshop & Leadership Experience
======
* Lead Organizer & Presenter: CBIOMES Workshop on Machine Learning Methods for Time-Series Data (2026)
* Committee Member: Durham University Postgraduate Research Conference (2022)
* Chairman: Delta Tau Delta, Wittenberg University (2013-2016)

---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Optimal intensive care outcome prediction over time using machine learning.
subtitle: ''
summary: ''
authors:
- C Meiring
- A Dixit
- S Harris
- NS MacCallum
- DA Brealey
- PJ Watkinson
- A Jones
- S Ashworth
- R Beale
- SJ Brett
- M Singer
- A Ercole
tags:
- '""'
categories: []
date: '2018-01-01'
lastmod: 2021-07-04T13:15:50+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2021-07-04T12:15:50.804391Z'
publication_types:
- '2'
abstract: 'BACKGROUND: Prognostication is an essential tool for risk adjustment and
  decision making in the intensive care unit (ICU). Research into prognostication
  in ICU has so far been limited to data from admission or the first 24 hours. Most
  ICU admissions last longer than this, decisions are made throughout an admission,
  and some admissions are explicitly intended as time-limited prognostic trials. Despite
  this, temporal changes in prognostic ability during ICU admission has received little
  attention to date. Current predictive models, in the form of prognostic clinical
  tools, are typically derived from linear models and do not explicitly handle incremental
  information from trends. Machine learning (ML) allows predictive models to be developed
  which use non-linear predictors and complex interactions between variables, thus
  allowing incorporation of trends in measured variables over time; this has made
  it possible to investigate prognosis throughout an admission. METHODS AND FINDINGS:
  This study uses ML to assess the predictability of ICU mortality as a function of
  time. Logistic regression against physiological data alone outperformed APACHE-II
  and demonstrated several important interactions including between lactate & noradrenaline
  dose, between lactate & MAP, and between age & MAP consistent with the current sepsis
  definitions. ML models consistently outperformed logistic regression with Deep Learning
  giving the best results. Predictive power was maximal on the second day and was
  further improved by incorporating trend data. Using a limited range of physiological
  and demographic variables, the best machine learning model on the first day showed
  an area under the receiver-operator characteristic curve (AUC) of 0.883 (σ = 0.008),
  compared to 0.846 (σ = 0.010) for a logistic regression from the same predictors
  and 0.836 (σ = 0.007) for a logistic regression based on the APACHE-II score. Adding
  information gathered on the second day of admission improved the maximum AUC to
  0.895 (σ = 0.008). Beyond the second day, predictive ability declined. CONCLUSION:
  This has implications for decision making in intensive care and provides a justification
  for time-limited trials of ICU therapy; the assessment of prognosis over more than
  one day may be a valuable strategy as new information on the second day helps to
  differentiate outcomes. New ML models based on trend data beyond the first day could
  greatly improve upon current risk stratification tools.'
publication: '*PLoS One*'
---

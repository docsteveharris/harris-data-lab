---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Natural language processing for mimicking clinical trial recruitment in critical
  care: a semi-automated simulation based on the LeoPARDS trial.'
subtitle: ''
summary: ''
authors:
- HC Tissot
- AD Shah
- D Brealey
- Steve Harris
- R Agbakoba
- A Folarin
- L Romao
- L Roguski
- R Dobson
- FW Asselbergs
tags:
- '""'
categories: []
date: '2020-01-01'
lastmod: 2021-07-04T13:15:52+01:00
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
publishDate: '2021-07-04T12:15:52.368569Z'
publication_types:
- '2'
abstract: Clinical trials often fail to recruit an adequate number of appropriate
  patients. Identifying eligible trial participants is resource-intensive when relying
  on manual review of clinical notes, particularly in critical care settings where
  the time window is short. Automated review of electronic health records (EHR) may
  help, but much of the information is in free text rather than a computable form.
  We applied natural language processing (NLP) to free text EHR data using the CogStack
  platform to simulate recruitment into the LeoPARDS study, a clinical trial aiming
  to reduce organ dysfunction in septic shock. We applied an algorithm to identify
  eligible patients using a moving 1-hour time window, and compared patients identified
  by our approach with those actually screened and recruited for the trial, for the
  time period that data were available. We manually reviewed records of a random sample
  of patients identified by the algorithm but not screened in the original trial.
  Our method identified 376 patients, including 34 patients with EHR data available
  who were actually recruited to LeoPARDS in our centre. The sensitivity of CogStack
  for identifying patients screened was 90% (95% CI 85%, 93%). Of the 203 patients
  identified by both manual screening and CogStack, the index date matched in 95 (47%)
  and CogStack was earlier in 94 (47%). In conclusion, analysis of EHR data using
  NLP could effectively replicate recruitment in a critical care trial, and identify
  some eligible patients at an earlier stage, potentially improving trial recruitment
  if implemented in real time.
publication: '*IEEE J Biomed Health Inform*'
---

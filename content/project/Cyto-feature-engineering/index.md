---
date: "2020-02-28T00:00:00Z"
external_link: ""
image:
  caption: 
  focal_point: Smart
links:
- icon: file-contract
  icon_pack: fas
  name: Github
  url: https://github.com/aef1004/cyto-feature_engineering
slides: 
summary: 
tags: 
- R
title: Cyto-feature engineering- A novel pipeline for flow cytometry analysis
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

Flow cytometers can now analyze up to 50 parameters per cell and millions of cells per sample;
however, conventional methods to analyze data are subjective and time-consuming. To address these
issues, we have developed a novel analysis pipeline to identify a plethora of cell populations efficiently.
Coupled with feature engineering and immunological context, researchers can immediately extrapolate
novel discoveries through easy-to-understand plots. The R-based pipeline uses Fluorescence Minus One
(FMO) controls or distinct population differences to develop thresholds for positive/negative marker
expression. The continuous data is transformed into binary data, capturing a positive/negative biological
dichotomy often of interest in characterizing cells. Next, a filtering step refines the data, from all
identified cell phenotypes to populations of interest. The data can be partitioned by immune lineages and
statistically correlated to other experimental measurements. The pipeline’s modular nature allows
customization of statistical testing, adoption of alternative initial gating steps, and incorporation of otherdatasets. Validation of this pipeline through manual gating of two datasets (murine splenocytes and
human whole blood) confirmed its accuracy in identifying even rare subsets. Lastly, this pipeline can be
applied in all disciplines utilizing flow cytometry regardless of cytometer or panel design.

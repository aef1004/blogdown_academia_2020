---
abstract: Flow cytometers can now analyze up to 50 parameters per cell and millions of cells per sample; however, conventional methods to analyze data are subjective and time-consuming. To address these issues, we have developed a novel flow cytometry analysis pipeline to identify a plethora of cell populations efficiently. Coupled with feature engineering and immunological context, researchers can immediately extrapolate novel discoveries through easy-to-understand plots. The R-based pipeline uses Fluorescence Minus One (FMO) controls or distinct population differences to develop thresholds for positive/negative marker expression. The continuous data is transformed into binary data, capturing a positive/negative biological dichotomy often of interest in characterizing cells. Next, a filtering step refines the data from all identified cell phenotypes to populations of interest. The data can be partitioned by immune lineages and statistically correlated to other experimental measurements. The pipeline’s modularity allows customization of statistical testing, adoption of alternative initial gating steps, and incorporation of other datasets. Validation of this pipeline through manual gating of two datasets (murine splenocytes and human whole blood) confirmed its accuracy in identifying even rare subsets. Lastly, this pipeline can be applied in all disciplines utilizing flow cytometry regardless of cytometer or panel design. The code is available at https://github.com/aef1004/cyto-feature_engineering.

authors:
- Amy Fox
- Taru S. Dutt
- Burton Karger
- Mauricio Rojas
- Andrés Obregón-Henao
- G. Brooke Anderson
- Marcela Henao-Tamayo 

date: "2020-05-06T00:00:00Z"
doi: "10.1038/s41598-020-64516-0"
featured: true
image:
  caption: ''
  focal_point: ""
  preview_only: false
links: null
projects: null
publication: In *Scientific Reports*
publication_short: 
publication_types:
- "2"
publishDate: "2020-05-06T00:00:00Z"
summary: The paper describes a novel analysis pipeline for flow cytometry data. The pipeline has the ability to identify all cell populations in a sample and it can be applied in all disciplines utilizing flow cytometry regardless of cytometer or panel design.  
tags:
- Source Themes
title: "Cyto-Feature Engineering: A Pipeline for Flow Cytometry Analysis to Uncover Immune Populations and Associations with Disease"
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}



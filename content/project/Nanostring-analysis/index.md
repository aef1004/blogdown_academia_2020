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
  url: https://github.com/aef1004/Nanostring_analysis
slides: 
summary: 
tags: 
- R
title: Automated nanostring analysis
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---
NanoString nCounter is a technology used to assess gene expression data. I was recently approached by a colleague that spent weeks copy and pasting data into GraphPad to analyze the the data. In response, I built a pipeline that performs automated statistical analysis for the Nanostring data. The pipeline reads in and cleans the data that contains hundreds of genes per study animal. It then tests each gene-mouse group pair for normality, similar variances, and then performs the appropriate statistical test (t-test or Wilcox Mann-Whitney) based on the results. This pipeline reduces analysis time from 1 week to under 1 minute.

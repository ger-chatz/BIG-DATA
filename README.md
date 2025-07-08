# Big Data and High-Dimensional Analysis in R

## Overview

This repository presents a series of projects showcasing how statistical models and R programming are applied to **large-scale** and **high-dimensional** datasets across various domains, including **genomics**, **airline transportation**, and **network science**.

It highlights the dual challenges in modern data science:
- Datasets with **millions of observations** (big data)
- Datasets with **thousands of variables and few observations** (high-dimensional)

All work was completed in the context of applied coursework in the MSc in Applied Statistics.

---

## Projects Covered

- **Genomics**: Gene expression dataset with **20,172 features × 60 samples** (Leukemia study)  
  → A classic **"large p, small n"** problem involving variable selection, PCA, and multiple testing (FWER, FDR)

- **Airline Flights (USA)**: Flight-level data with **millions of rows**  
  → Regression modeling, feature engineering, model selection using `biglm`

- **Network Analysis**: Real-world directed graph with user interactions  
  → Community detection, centrality, and graph visualization using `igraph`

---

## Key Techniques & Concepts

- **Principal Component Analysis (PCA)** for dimensionality reduction  
- **Multiple testing corrections**: Bonferroni, FDR, pFDR, and q-values  
- **Model selection**: AIC, BIC, likelihood ratio tests  
- **GLMs and stepwise regression** on large datasets  
- **Graph theory**: degree, betweenness, clustering in directed networks

---

## Tools Used

- **R**  
  - `biglm`, `limma`, `igraph`, `ggplot2`, `tidyverse`  
- Efficient handling of large data with memory-aware tools  
- Visualization and diagnostics for both high-p and high-n settings

---

## Applications Across Fields

Although examples come from **genetics**, **air travel**, and **social networks**, the methods are broadly applicable in:
- Business & marketing analytics  
- Health informatics  
- Social science research  
- High-throughput bioinformatics

This repository reflects the increasing importance of **statistical thinking at scale**, where choosing the right model, correction method, or visualization becomes critical under **data-rich conditions**.

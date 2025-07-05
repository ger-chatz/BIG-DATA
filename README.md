# Big Data Applications and Analysis

This repository contains various data analysis exercises related to bioinformatics, big data regression, and network modeling. Each exercise demonstrates practical use of R for exploratory analysis, dimensionality reduction, hypothesis testing, and modeling.

---

## 📁 Contents

### 🧬 Exercise 1: Gene Expression Analysis (Leukemia Dataset)
- **Dataset**: Gene expression data of 60 bone marrow samples across 20,172 genes
- **Goal**: Compare gene expression between AML (Acute Myeloid Leukemia) and NOL (Non-leukemia)
- **Tasks**:
  - Exploratory data analysis (boxplots, QQ-plots, heatmaps)
  - Principal Component Analysis (PCA) on raw and transposed data
  - Independent t-tests per gene
  - p-value distribution and null hypothesis proportion estimation
  - FWER, FDR, and pFDR control at α = 0.01
  - Visualize significant genes and PCA colored by FDR significance

### ✈️ Exercise 2: Big Data Regression (Airline Delay)
- **Dataset**: US flight data from 1987–2008 (used: 1993)
- **Goal**: Model arrival delay based on flight characteristics
- **Variables**:
  - Month, weekday, distance, departure delay, departure time
- **Model**: GLM to predict arrival delay
- **Results**:
  - Interpretations of coefficients
  - BIC/AIC model selection
  - Seasonal delay pattern comparison

### 👥 Exercise 3: Social Network Analysis
- **Data**: Friendship graph of 20 individuals from personal circles
- **Goal**: Visualize and cluster a social graph
- **Tasks**:
  - Create adjacency matrix
  - Compute edge density and centrality
  - Cluster and compare to real-life groups (school, family, university, etc.)
  - Analyze mismatches and clustering logic

---

## 📊 Tools & Libraries

```r
ggplot2
pheatmap
stats
igraph
limma
qvalue
biglm

📌 Notes
All analyses are implemented in R

PCA and statistical testing are based on large-scale bioinformatics workflows

Visualization and network clustering provide intuitive insights beyond numerical output

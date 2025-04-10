# Multilevel Modelling of Patient Satisfaction in Hospitals

This repository contains a detailed multilevel modeling analysis based on a fictitious dataset of patient satisfaction in hospitals. The project is structured as an R Markdown (`.Rmd`) file that walks through exploratory data analysis, model building, validation, and interpretation of a multilevel model using the `lme4` package in R.

## 📁 Files

- `Instructions.Rmd`: Main analysis file containing code and interpretation.
- `hospSatisfaction.Rda`: Simulated dataset used for the analysis.

## 🧠 Project Overview

The goal is to examine how patient satisfaction varies across hospitals and what individual and institutional-level factors contribute to this variation. The dataset includes both patient-level (e.g., age, sex, readmission) and hospital-level variables (e.g., hospital type, area).

## 🛠 Methods

- Multilevel models (`lmer` from the `lme4` package)
- Model comparison using ANOVA
- Visual diagnostics (residual plots, caterpillar plot, predicted vs. observed)

## 🧾 Key Findings

- A random intercept and random slope model (Model 7) best captures variation.
- 65.8% of satisfaction score variance is explained by differences between hospitals.
- Hospital type, area, sex, age, and readmission status significantly influence satisfaction.
- Remote hospitals and private hospitals generally show higher satisfaction levels.

## 📊 Visual Outputs

- Histograms and boxplots of satisfaction across categories
- Residual analysis
- Caterpillar plots for random effects
- Observed vs. predicted plot for model accuracy

## 🔍 Citation Reference

Liu, M., et al. (2023). Patient healthcare experiences of cancer hospitals in China: A multilevel modeling analysis based on a national survey. *Frontiers in Public Health, 11*, 1059878. [DOI link](https://doi.org/10.3389/fpubh.2023.1059878)

## 👨‍💻 Author

**Parth Chandan**  
Master of Public Health | Health Data Science  
[LinkedIn](https://www.linkedin.com/in/parthchandan)  

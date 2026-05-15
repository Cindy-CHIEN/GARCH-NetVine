# GARCH-NetVine

This repository contains the R implementation of the empirical analysis and methodology proposed in our study on dynamic dependence modeling using GARCH and vine copula-based network structures.

This repository accompanies the corresponding academic research paper.

---

# Project Description

The project focuses on modeling the dependence structure among financial assets in the S&P 100 index using GARCH-type marginal models combined with vine copula techniques.

The repository includes:

- Data collection and preprocessing
- Estimation of marginal GARCH models
- Vine copula construction
- Dependence network analysis
- Empirical experiments and visualization

The empirical analysis is conducted using daily stock returns from companies in the S&P 100 index across multiple industrial sectors.

---

# Data Source

Daily adjusted closing prices were obtained from Yahoo Finance.

- Data period: January 1, 2019 – December 31, 2024
- Market index: S&P 100
- Frequency: Daily

Yahoo Finance:  
https://finance.yahoo.com/

---

# Package Requirements

The project is implemented in R.

Required packages include:

```r
install.packages(c(
  "quantmod",
  "rugarch",
  "VineCopula",
  "igraph",
  "dplyr",
  "tidyr",
  "ggplot2",
  "PerformanceAnalytics",
  "xts",
  "zoo"
))

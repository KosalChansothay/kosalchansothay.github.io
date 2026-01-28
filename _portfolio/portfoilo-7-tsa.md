---
title: "Time Series Analysis: Cambodia Provincial Rainfall"
excerpt: "ARIMA and SARIMA modeling for rainfall forecasting in Pursat Province, Cambodia"
collection: portfolio
date: 2026-01-28
---

## Project Overview

This is an academic project for the **Time Series Analysis** course at the **Institute of Technology of Cambodia (ITC)**, Department of Applied Mathematics and Statistics. The study focuses on rainfall forecasting for **Pursat Province**, utilizing ARIMA and SARIMA modeling techniques to aid in agricultural planning and disaster preparedness.

### Key Contributions

* **Data Integration:** Loaded and processed rainfall data from the Humanitarian Data Exchange (HDX) covering over **45 years** (1981–2026).
* **Provincial Analysis:** Constructed monthly aggregated time series specifically for Pursat Province, consolidating data from dekadal (10-day) intervals.
* **Stationarity Assessment:** Performed rigorous statistical validation using the **Augmented Dickey-Fuller (ADF)** test and seasonal differencing to ensure data stationarity.
* **Model Development:** Developed and compared multiple model architectures including AR, MA, ARMA, ARIMA, and SARIMA using rolling one-step-ahead forecast evaluation.
* **Robust Evaluation:** Implemented a strict **no-leakage train-test split** with a 60-month test horizon to ensure out-of-sample reliability.
* **Forecasting:** Generated a **24-month rainfall forecast** with 95% confidence intervals.

### Key Findings

* **Strong Seasonality:** Identified a dominant **12-month cyclical pattern** reflecting the region's monsoon (May–October) and dry season (November–April).
* **Model Performance:** The **SARIMA model** outperformed other specifications, achieving the most consistent RMSE (Root Mean Square Error) across rolling forecast windows.
* **Residual Diagnostics:** Validated model adequacy through autocorrelation testing and normality assessments.
* **Practical Application:** The forecast provides actionable localized predictions crucial for water resource management and crop cycle planning.

### Technologies Used

* **Data Processing:** Python, pandas, NumPy
* **Time Series Analysis:** statsmodels (ARIMA, SARIMAX, ACF/PACF, seasonal decomposition)
* **Visualization:** Plotly (interactive charts and heatmaps)
* **Statistical Testing:** scipy, ADF test, Ljung-Box test, Shapiro-Wilk test
* **Metrics:** scikit-learn (MAE, RMSE, R²)
* **Presentation:** Quarto RevealJS

### Methodology Highlights

| Aspect | Approach |
| :--- | :--- |
| **Data Level** | Provincial (Pursat) |
| **Frequency** | Monthly aggregation (from dekadal data) |
| **Evaluation** | Rolling one-step-ahead forecasts (no data leakage) |
| **Test Period** | 60 months (5 years) |
| **Forecast Horizon** | 24 months ahead |
| **Model Selection** | Compared 20 specifications by RMSE |

### Course & Team Information

**Institution:** Institute of Technology of Cambodia  
**Department:** Applied Mathematics and Statistics  
**Course:** Time Series Analysis  
**Instructor:** Dr. SIM Tepmony  
**Group:** 01  
**Date:** January 2026

**Team Members:**
* CHEA Piseth
* KHUN Sithanut
* KOSAL Chansothay
* HENG Sopanha

### Resources

- [Interactive Presentation](https://kosalchansothay.github.io/TSA-Cambodia-National-Rainfall/#/title-slide)
* **Presentation:** Interactive Quarto RevealJS slide deck with executable Python code blocks.
* **Data Source:** Humanitarian Data Exchange (HDX)

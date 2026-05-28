# Real Estate Market Data Pipeline & Predictive Modeling

This repository contains an end-to-end data engineering and analytics project. It covers data processing, Exploratory Data Analysis (EDA), and predictive regression modeling built on property market data.

## Project Overview

The goal of this project is to clean, analyze, and model real estate transactional data. The workflow transforms raw property data into an optimized feature set to predict property sale prices using regression analysis.

## Tech Stack & Workflow

*   **Data Processing (Alteryx Designer):** 
    *   Ingested raw real estate transaction datasets.
    *   Executed missing data handling and strategic statistical imputation.
    *   Engineered additional domain-specific features to maximize model signal.
    *   Exported the cleaned pipeline output directly into a standalone `Final_Real_Estate` file.
*   **Exploratory Data Analysis (EDA):**
    *   Analyzed property distributions, neighborhood impacts, and housing categories.
    *   Identified statistical outliers and distribution skews across housing types.
    *   Mapped correlations between features and the target variable.
*   **Regression Modeling & Evaluation:**
    *   Isolated **`Price`** as the specific target variable for prediction.
    *   Partitioned the processed data into an **80:20 train-test split**.
    *   Trained a regression model to forecast property market value.
    *   Calculated final prediction errors on the unseen test set to evaluate overall performance.

##  Key Findings & Results

*   **EDA:** Property physical attributes and location-based features emerged as the strongest drivers of market value.
*   **Model Performance:** The regression model successfully minimizes prediction error when estimating final market prices, proving highly effective for real estate forecasting.

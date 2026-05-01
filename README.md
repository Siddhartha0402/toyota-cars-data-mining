# Toyota Cars Data Mining Analysis

## Project Overview

This project applies data mining techniques to analyze Toyota car data and identify the key factors that influence vehicle pricing, market segmentation, and predictive performance. The analysis includes clustering, classification, and regression modeling to extract meaningful insights from automotive data.

The goal of this project is to demonstrate a complete data mining workflow, including data preparation, exploratory data analysis, model development, model evaluation, and business interpretation.

## Business Problem

Automotive pricing is influenced by multiple factors such as vehicle age, mileage, fuel type, transmission type, horsepower, engine size, and vehicle condition. For dealerships, buyers, and analysts, understanding these patterns can improve pricing decisions, inventory planning, and customer segmentation.

This project answers three major questions:

1. Can Toyota cars be grouped into meaningful vehicle segments?
2. Can classification models accurately predict vehicle categories or outcomes?
3. Can regression models predict Toyota car prices using vehicle attributes?

## Dataset Description

The dataset contains Toyota car records with features related to pricing, mileage, age, technical specifications, and categorical vehicle attributes.

Key variables include:

- Price
- Age
- Mileage
- Fuel Type
- Horsepower
- Engine Size
- Transmission Type
- Doors
- Weight
- Other vehicle-related attributes

## Project Objectives

- Perform exploratory data analysis to understand Toyota car pricing patterns.
- Apply clustering techniques to identify natural vehicle groups.
- Build classification models and evaluate prediction performance.
- Build regression models to estimate Toyota car prices.
- Interpret results from both technical and business perspectives.

## Tools and Technologies

- Tableau
- Data Mining
- Predictive Modeling
- Regression Analysis
- Classification Analysis
- Cluster Analysis
- Exploratory Data Analysis
- Business Analytics

## Methodology

### 1. Data Cleaning and Preparation

The dataset was reviewed for missing values, incorrect data types, outliers, and inconsistent entries. Numerical and categorical variables were prepared for modeling through transformation, encoding, and feature selection.

### 2. Exploratory Data Analysis

Exploratory analysis was performed to understand relationships between price and key predictors such as age, mileage, horsepower, fuel type, and transmission type. Visualizations were used to identify pricing trends, correlations, and potential outliers.

### 3. Cluster Analysis

Clustering was used to group Toyota cars into similar segments based on selected vehicle attributes. This helped identify patterns among vehicles with similar pricing, usage, or technical characteristics.

### 4. Classification Analysis

Classification modeling was used to predict categorical outcomes from the dataset. Model performance was evaluated using accuracy, misclassification rate, and confusion matrix results.

The classification analysis achieved a misclassification rate of approximately **3.3%**, indicating strong predictive performance.

### 5. Regression Analysis

Regression modeling was used to predict Toyota car prices based on numerical and categorical vehicle attributes. The model helped identify the most important factors influencing vehicle price.

The regression model achieved an adjusted R² value of approximately **0.80**, indicating that the selected features explained a strong portion of the variation in vehicle price.

## Key Results

| Analysis Type | Objective | Key Result |
|---|---|---|
| Cluster Analysis | Segment similar Toyota vehicles | Identified meaningful vehicle groups based on pricing and technical attributes |
| Classification | Predict categorical vehicle outcomes | Misclassification rate: 3.3% |
| Regression | Predict Toyota car price | Adjusted R²: 0.80 |

## Project Files

- [Predictive Analysis Report](toyota-predictive-analysis-report)
- [Tableau Dashboard Workbook](toyota-data-visualization-dashboard)

## Key Insights

- Vehicle age and mileage are strong indicators of price depreciation.
- Technical attributes such as horsepower, engine size, and weight contribute to price variation.
- Clustering helped identify groups of Toyota cars with similar pricing and usage characteristics.
- Classification modeling produced strong predictive performance with a low misclassification rate.
- Regression modeling explained a significant portion of Toyota car price variation.

## Repository Structure

```text
toyota-cars-data-mining/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
├── reports/
├── src/
├── tableau/
├── visuals/
│
├── .gitignore
├── README.md
└── requirements.txt

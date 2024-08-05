# Online Retail Store Performance Analysis

This repository contains the analysis and visualizations of an online retail store's performance data using Power BI. The objective is to provide insights for strategic decision-making to the CEO and CMO.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Preparation](#data-preparation)
3. [Analysis and Visualizations](#analysis-and-visualizations)
   - [Revenue Trends for 2011](#revenue-trends-for-2011)
   - [Top 10 Countries by Revenue (Excluding UK)](#top-10-countries-by-revenue-excluding-uk)
   - [Top 10 Customers by Revenue](#top-10-customers-by-revenue)
   - [Demand by Region (Excluding UK)](#demand-by-region-excluding-uk)
4. [Conclusion](#conclusion)
5. [Files in the Repository](#files-in-the-repository)

## Introduction

The goal of this analysis is to evaluate the current business performance of an online retail store and provide insights that will guide expansion decisions. The CEO and CMO are interested in understanding key performance metrics from both operational and marketing perspectives.

## Data Preparation

The dataset used for this analysis is `Online Retail.xlsx`. The data was cleaned to ensure accuracy:
- Removed records where `Quantity` < 1.
- Removed records where `UnitPrice` < $0.

These steps ensured that the analysis was based on high-quality data, free from errors.

## Analysis and Visualizations

### Revenue Trends for 2011

- **Objective**: To view the time series of revenue data for 2011 on a monthly basis.
- **Insights**: This analysis helps in understanding seasonal trends and forecasting for the next year.

### Top 10 Countries by Revenue (Excluding UK)

- **Objective**: To identify the top 10 countries generating the highest revenue, excluding the United Kingdom.
- **Insights**: Germany, France, and the Netherlands are major revenue contributors, guiding potential areas for expansion.

### Top 10 Customers by Revenue

- **Objective**: To identify the top 10 customers by revenue.
- **Insights**: This information helps in targeting high-value customers and ensuring they remain satisfied with the products.

### Demand by Region (Excluding UK)

- **Objective**: To analyze product demand across different regions, excluding the United Kingdom.
- **Insights**: Countries like Germany, France, and Australia have high demand, guiding the company's expansion strategy.

## Conclusion

The analysis provided key insights into revenue trends, top markets, high-value customers, and regional demand. Based on these insights, the following strategic recommendations are made:
- Focus on targeted marketing and promotional activities.
- Implement customer retention programs for high-value customers.
- Expand into regions with high product demand.

## Files in the Repository

- `Online_Retail.xlsx`: The original dataset used for analysis.
- `OnlineRetailAnalysis.pbix`: The Power BI file containing the data cleaning and visualizations.

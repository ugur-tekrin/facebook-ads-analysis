# Facebook Ads Performance Analysis

This project analyzes Facebook advertising campaign performance using Python data analysis and visualization libraries.

## Project Overview

The goal of this analysis is to evaluate the effectiveness of advertising campaigns by examining spending, return on marketing investment (ROMI), and relationships between key performance metrics.

Using Pandas for data manipulation and Seaborn/Matplotlib for visualization, we explore how advertising spend impacts campaign results and identify patterns in performance metrics.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The dataset contains daily statistics of Facebook advertising campaigns, including:

- ad_date – date of the advertisement
- campaign_name – campaign name
- total_spend – total advertising cost
- total_impressions – number of impressions
- total_clicks – number of clicks
- total_value – conversion value generated
- CPC – cost per click
- CPM – cost per 1000 impressions
- CTR – click-through rate
- ROMI – return on marketing investment

## Analysis Steps

### 1. Data Preparation
- Loaded dataset using Pandas
- Filtered data for year 2021
- Grouped data by date and campaign

### 2. Time Series Analysis
Created line charts showing:

- Daily advertising spend in 2021
- Daily ROMI in 2021
- 7-day moving average for spend and ROMI (trend visualization)

### 3. Campaign Performance Analysis
Grouped data by campaign name to analyze:

- Total spend per campaign
- Average ROMI per campaign

### 4. Distribution Analysis
Visualized distributions using:

- Box plot → distribution of daily ROMI by campaign
- Histogram → overall ROMI distribution

### 5. Correlation Analysis
Generated a heatmap to analyze relationships between numerical variables.

Key focus:
- Identifying variables most correlated with total_value
- Understanding relationships between spend, impressions, clicks and revenue

### 6. Regression Analysis
Created scatter plot with linear regression (lmplot) to evaluate relationship between:

total_spend vs total_value

This helps understand whether higher ad spend leads to higher conversion value.

## Key Insights

- Higher advertising spend generally leads to higher total conversion value
- Some campaigns show more stable ROMI performance than others
- Certain metrics show strong positive correlation with total_value

## Project Structure

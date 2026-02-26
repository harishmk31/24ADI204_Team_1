
# Data Visualization & EDA Code

## Description
This folder contains the Python scripts and notebooks used for
Exploratory Data Analysis (EDA) and visualization of the IPL 2025
Auction dataset.

The objective of this module is to transform cleaned data into
meaningful visual insights that support data-driven decision making.

## Tools & Libraries Used
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn (for advanced stages)

## Analysis Performed

### 1. Univariate Analysis
- Age distribution
- Role distribution
- Cap status distribution
- Reserve price distribution
- IPL matches distribution

### 2. Bivariate Analysis
- Reserve Price vs Role
- Reserve Price vs Cap Status
- Age vs Reserve Price
- IPL Matches vs Reserve Price
- Correlation heatmap

### 3. Outlier Detection
- IQR method used for detecting statistical outliers
- Outliers retained as they represent elite players

## Key Insights
- Reserve price distribution is positively skewed
- Capped players generally have higher reserve prices
- Player experience influences market valuation
- Role specialization impacts price variation

## Purpose
The visualization code supports:
- Understanding player valuation trends
- Identifying undervalued players
- Preparing dataset for PCA and dimensionality reduction
- Building the final storytelling dashboard

"""



# IPL 2025 Auction – Cleaned Dataset

## File Name
cricket_cleaned.csv

## Description
This file contains the cleaned and preprocessed version of the IPL 2025 Auction dataset.
The original raw dataset was processed to improve data quality and ensure consistency.
The dataset is now free from missing values and ready for analysis.

## Cleaning Steps Performed
- Removed unnecessary initial rows
- Renamed columns for clarity
- Corrected swapped values between Cap_Status and No_of_Matches
- Converted caps and match columns to numeric format
- Handled missing values using median (numerical) and mode (categorical)
- Imputed State_Association only for Indian players
- Converted Reserve_Price from text format (Cr/Lakh) to numeric format
- Detected statistical outliers using IQR method (retained for authenticity)
- Removed duplicate records

## Outlier Summary
Outliers were detected using the IQR method:
- Reserve_Price_Numeric – 87 outliers
- IPL_Matches – 278 outliers
- T20_Caps – 214 outliers
- ODI_Caps – 201 outliers
- Test_Caps – 132 outliers

These outliers were retained because they represent elite and highly experienced players rather than data errors.

## Final Dataset Status
- Total Rows: 575
- Total Columns: 22
- Missing Values: 0
- Dataset ready for EDA and PCA

## Purpose
This cleaned dataset will be used for:
- Univariate and Bivariate Analysis
- Correlation Analysis
- Dimensionality Reduction using PCA
- Identifying undervalued players using data-driven insights
"""



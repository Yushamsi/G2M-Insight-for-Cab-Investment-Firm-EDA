# Cab Industry Investment Analysis for XYZ Firm

## Overview
This project provides an in-depth analysis of two leading cab companies to assist XYZ, a private firm in the US, in their investment decision-making process. With the cab industry experiencing significant growth, our analysis focuses on identifying the company with the best potential for future profitability.

## Project Objective
To equip XYZ with actionable insights through a data-driven examination of market dynamics, customer preferences, and financial performance of two major cab companies, thereby informing their Go-to-Market (G2M) strategy.

## Data Description
The analysis utilizes four primary datasets spanning from January 31, 2016, to December 31, 2018:
1. **Cab_Data.csv** - Transaction details for the cab companies.
2. **Customer_ID.csv** - Links customer demographics to unique identifiers.
3. **Transaction_ID.csv** - Links transactions to customers with payment details.
4. **City.csv** - Information on US cities, including population and cab users.

## Analysis Workflow
1. **Data Loading and Cleaning**:
   - Handling missing values and outliers.
   - Removing duplicates.
   - Verifying the integrity of transactional and customer data.

2. **Exploratory Data Analysis (EDA)**:
   - Investigating customer demographics, payment modes, and transaction patterns.
   - Analyzing profitability, market share, and operational metrics by city and cab company.

3. **Insights and Recommendations**:
   - Identified trends and preferences that impact cab usage and company profitability.
   - Utilised regression analysis to forecast future market behaviors and profitability
     
## Libraries and Methods Used
- **Pandas**: For data manipulation and analysis (e.g., `read_csv`, `dropna`, `groupby`).
- **Matplotlib** and **Seaborn**: For creating visualizations (e.g., `plot`, `bar`).
- **NumPy**: For numerical operations (e.g., `array`, `mean`).
- **SciPy**: For additional scientific computations (e.g., `stats`).
- **scikit-learn**: For machine learning and predictive modeling (`LinearRegression`).

## Key Findings
- **Market Share and Profitability**: Yellow Cab shows a higher overall profitability and market presence compared to Pink Cab.
- **Customer Preferences**: Analyses of age distribution, payment methods, and gender preferences provide insights into consumer behavior.
- **Investment Recommendation**: Based on the analysis, Yellow Cab is recommended as the preferable investment opportunity due to its robust market position and higher profitability projections.

## Repository Contents
- **Analysis.ipynb** - Jupyter notebook with detailed analysis.
- **Data/** - Directory containing all datasets used in the analysis.
- **Presentation.pptx** - Executive presentation summarizing key findings.

## Installation
To run this project, ensure you have Python installed and execute the following:
```bash
pip install -r requirements.txt
jupyter notebook

# US Childcare Analysis Project

## Overview
This project conducts an in-depth analysis of childcare costs and their relationship with demographic, economic, and employment factors in the United States. The goal is to unearth patterns that can inform policy-making and deepen the understanding of childcare affordability dynamics.

## Data
The analysis uses two primary datasets:
- Childcare costs by county over several years.
- Demographic and economic data for these counties, including variables such as median household income, employment rates across sectors, racial demographics, and household types.

## Methods
The project pipeline includes:

- **Data Cleaning**: Addressing missing data and ensuring consistency.
- **Exploratory Data Analysis (EDA)**: Using both visual and quantitative methods to explore the data.
- **Feature Engineering**: Creating new features that could serve as meaningful predictors.
- **Data Imputation**: Imputing missing childcare cost data using K-Nearest Neighbors.
- **Feature Selection**: Identifying key predictors with RFECV and SFS.
- **Regression Analysis**: Modeling childcare costs against other factors using OLS regression.
- **Clustering**: Segmenting counties into clusters based on demographics and employment using K-Means.
- **ANOVA Testing**: Performing ANOVA to determine the statistical significance of differences between clusters.

## Results
The analysis delineates complex interactions between demographics, household structures, industry employment, and childcare expenses, revealing distinct county clusters with unique profiles.

## Real-World Implications
Insights from this analysis could guide targeted efforts to alleviate the childcare cost burden on specific communities.

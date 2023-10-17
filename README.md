# Feature-Sensitivity-analysis

This repository contains an example of feature sensitivity analysis using Support Vector Regression (SVR). 
## Workflow

The workflow in this project involves the following steps:

1. Data Standardization and Splitting: Start by standardizing the selected dataset and splitting it into training and test datasets. Note that only continuous variables are standardized, as binary and categorical variables don't require scaling. The training dataset covers 10 days from 2018/12/03 to 2018/12/13, while the test dataset spans six days from 2018/12/14 to 2018/12/19.

2. SVR Modeling: Train six SVR models (SVR-A to SVR-F) using different feature sets. SVR-A includes all features, while the others exclude one group of features at a time (see Modelling Table). Calculate RMSE for each model compared to the reference model (SVR-A).

3. Feature Importance Analysis: Perform feature sensitivity analysis using Mean Absolute Deviation (MAD).

![workflow](https://github.com/IvaMate/Feature-Sensitivity-analysis/assets/55032190/42ec277d-8795-41e5-8ce4-1037824c9c32)
![features](https://github.com/IvaMate/Feature-Sensitivity-analysis/assets/55032190/ef8cc659-8db8-4d96-87d3-efa250690b12)


# Predictive-Analytics-with-R
# Bike Rental Demand Forecasting in R
This project leverages R for exploratory data analysis, feature engineering, and predictive modeling to forecast hourly bike rental demand using a dataset from Washington City. With over 17,000 observations across two years, the study investigates environmental and temporal factors affecting rentals.

# Key Objectives
- Identify significant predictors of hourly bike rentals.
- Explore linearity and interaction effects among variables.
- Compare model performances to determine the best predictive model.

# Tools & Techniques
- **Language:** R  
- **Packages:** `ggplot2`, `dplyr`, `caret`, `rpart`, `randomForest`  
- **Models:** Multiple Linear Regression, Regression Tree, Random Forest  
- **Evaluation Metrics:** RMSE, Adjusted R²

# Results
- **Best Model:** Random Forest with an Adjusted R² of **85.88%** and low RMSE on both training and test sets.
- Identified **hour**, **temperature**, and **weekday** as strong predictors.
- Interaction analysis revealed peak rental periods (8–9 AM and 6–7 PM), influenced by temperature.

# Business Insights
- Scale up bike availability during peak hours.
- Focus marketing efforts to increase casual user engagement.
- Use demand predictions for optimizing maintenance schedules and bike station placements.



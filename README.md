
Data Analysis and Regression Project Report
Name: Fathima Khader
Date: 07/10/2023

Introduction
This project focuses on analyzing airline delay data using regression techniques. The dataset contains various independent variables such as YEAR, MONTH, DAY, AIRLINE, and more, with ARRIVAL_DELAY as the dependent variable.

Data Import and Cleaning
The dataset was imported from a CSV file named f2.csv.
Initial exploration revealed missing values, which were addressed by deleting rows with missing values.
Data Exploration
5-Point Summary
Analysis revealed insights into the distribution and summary statistics of various variables.
Frequency Analysis
Frequency analysis provided an overview of the distribution of flights among different airlines.
Boxplot
Boxplots were used to visualize the distribution of arrival delays across different months.
Histogram
Histograms were utilized to observe the distribution of arrival delays, revealing skewness towards higher delay values.
Correlation
Correlation analysis identified the relationship between various independent variables and arrival delay.
Scatterplot
Scatterplots were employed to visualize the relationship between independent variables and arrival delay.
Regression Analysis
The PROC REG procedure was used to build a regression model predicting arrival delay based on several independent variables.
Parameter estimates and their interpretations were provided for each variable in the model.
Assumptions of linearity, normality, independence, and constant variance were assessed.
Model Refinement
Multicollinearity was addressed by removing variables with high variance inflation factors (VIF).
Outliers and influential points were identified and removed from the dataset.
Model equations were generated and evaluated based on model selection techniques.
Model Performance
The dataset was split into training and testing sets.
Model performance metrics such as RMSE and R-squared were compared between training and testing sets.
Diagnostics were conducted to assess model assumptions and performance.
Final Model and Predictions
The final model equation was generated, highlighting the effect of each independent variable on arrival delay.
Predictions were made for specific scenarios using the final model, including confidence intervals.
Conclusion
This project successfully analyzed airline delay data using regression techniques, providing insights into the factors influencing arrival delay. The final model demonstrated good performance in predicting arrival delays, with implications for airline operations and scheduling.

Figures:

Fig. 1: First 5 Observations
Fig. 2: 5-Point Summary
Fig. 3: Frequency Distribution of Airlines
Fig. 4: Boxplot of Arrival Delay by Month
Fig. 5: Histogram of Arrival Delay
Fig. 6: Correlation Matrix
Fig. 7: Scatterplots (a-i)
Fig. 8: Regression Parameter Estimates
Fig. 9: Importance Ranking of Variables
Fig. 10: Multicollinearity Assessment
Fig. 11: Outliers and Influential Points (a-h)
Fig. 12: Model Equation
Fig. 13: Data Splitting
Fig. 14: Model Performance Statistics
Fig. 15: RMSE and MAE Comparison
Fig. 16: Diagnostics Assessment
Fig. 17: Model Equation (Final)
Fig. 18: Effect of Independent Variables
Fig. 19: Prediction Results
Please refer to the corresponding figures for detailed visualizations and analysis.

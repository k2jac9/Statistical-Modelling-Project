# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
- **Objective:** 

Create an app that is powered by an statiscal model across different regions.
Provide valuable insights into bike-sharing and points of interest data. It involves data retrieval, analysis, visualization, and modeling.

- **Goals:**
   1. Determine key metrics for assessing API quality.
   2. Collect and preprocess data from various APIs.
   3. Apply statistical models to analyze data.
   4. Compare the quality of API coverage across different regions.

## Process
### Step 1: Data Collection
- **Method:** Utilize Python libraries such request, pandas and os to secure API keys in order gather data from various APIs.
- **Best Practice:** Ensure to handle exceptions and errors during data collection to maintain robustness in the data pipeline.

### Step 2: Data Cleaning and Preprocessing
- **Method:** Use Pandas for data cleaning, handling missing values, outliers, etc... and preprocessing, normalizing, formatting encoding  data.
- **Best Practice:** Create reusable functions for preprocessing steps to maintain code efficiency and readability.

### Step 3: Exploratory Data Analysis (EDA)
- **Method:** Conduct EDA using Pandas and visualization libraries like  matplotlib and seaborn to understand data distributions and patterns.
- **Best Practice:** Document the findings and insights from EDA clearly, as it will guide the model selection and interpretation of results.

### Step 4: Statistical Modeling
- **Method:** Apply statistical models such a regression analysis using libraries like statsmodels and sklearn.
- **Best Practice:** Ensure to validate the model using techniques like cross-validation and adjust based on model diagnostics.

### Step 5: Evaluation and Comparison
- **Method:** Evaluate the model's performance using appropriate metrics (like MSE, R-squared) and compare API coverage across different regions.
- **Best Practice:** Use visualizations to present the comparisons, making them more interpretable for non-technical stakeholders.

## Results
- **Findings:**  The R-squared value measures the goodness of fit of the regression model. In the case, it's 0.015.
- **Interpretation:** The regression model has a low R-squared value, suggesting that it may not explain much of the variation in the dependent variable.

## Challenges 
- **Data Quality:** Issues with missing or inconsistent data from APIs.
- **Model Complexity:** Difficulty in choosing the right model or tuning model parameters.
- **Interpretation:** Challenges in interpreting the statistical results in the context of API quality.

## Future Goals
- **Enhancements:** With more time, I would explore advanced modeling techniques like machine learning to predict API quality.
- **Expansion:** Expand the study to include more regions or different types of APIs.
- **Automation:** Develop an automated system for continuous monitoring and analysis of API quality.

### Presentation
![1](https://github.com/k2jac9/Final-Project-Statistical-Modelling/assets/5405628/1c03a309-1e5d-4757-945a-7acbe0dc8e64)
![2](https://github.com/k2jac9/Final-Project-Statistical-Modelling/assets/5405628/46843650-aad5-4d15-bcfb-ddaac23f9ef2)
![3](https://github.com/k2jac9/Final-Project-Statistical-Modelling/assets/5405628/7fa0c4b0-1440-4d9b-8569-0dd6cce16bee)
![4](https://github.com/k2jac9/Final-Project-Statistical-Modelling/assets/5405628/c3f834ac-7ac4-46ce-8ec0-4435f8ad6a71)
![5](https://github.com/k2jac9/Final-Project-Statistical-Modelling/assets/5405628/cb8018ab-9f24-420c-823d-2c8b3b6f0515)
![6](https://github.com/k2jac9/Final-Project-Statistical-Modelling/assets/5405628/f654b9f9-e274-4ea0-b341-94ddc96845e8)


Mean Squared Error: 0.10430008876730193
R-squared: -0.19739739051447214

The results for the Random Forest Regression model are as follows:

Mean Squared Error (MSE): Approximately 0.0064
R-squared (R2): Approximately - 0.925

This value is significantly lower than the MSE from the previous Linear Regression model. A lower MSE indicates that the Random Forest model's predictions are, on average, closer to the actual values. The MSE of approximately 0.0064 suggests that this model is a good fit for the data.

The R-squared value is a measure of how well the model's predictions match the actual data. An R-squared of 0.9259 (or about 92.59%) is quite high, which means that approximately 92.59% of the variance in the dependent variable (usage) is predictable from the independent variables (total_bikes, poi_distance) in the model.

This is a significant improvement over the Linear Regression model, which had a negative R-squared value. It indicates that the Random Forest model captures the relationships and patterns in the data much more effectively.
In summary, the Random Forest Regression model shows both a low Mean Squared Error and a high R-squared value, indicating that it is a very effective model for predicting the target variable with the given features. It seems to capture the underlying relationships in the data much better than the Linear Regression model previously used.

![8](https://github.com/k2jac9/Final-Project-Statistical-Modelling/assets/5405628/079ed144-1a7d-47e0-9b66-035868cb8e80)










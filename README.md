# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
- **Objective:** To analyze and compare the quality of API coverage in different regions using statistical modeling in Python.
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


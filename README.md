# Fraud_Prediction

## Problem Statement
The objective of this project is to utilize a Random Forest classifier to build a predictive model on a dataset related to fraud. In this scenario, individuals with taxable_income less than or equal to 30000 are labeled as "Risky," while others are labeled as "Good."

## Approach
The implementation is done in Python using a Jupyter notebook, following a comprehensive machine learning lifecycle:

1. **Data Cleaning and Analysis:**
   - Performed data cleaning and analysis using pandas for efficient data processing.

2. **Visualization:**
   - Utilized seaborn for data visualization to gain insights and understand patterns within the dataset.

3. **Label Encoding:**
   - Applied Label Encoder to transform categorical variables into numerical format, facilitating the model training process.

4. **Stratified Sampling:**
   - Employed stratified sampling during data splitting to ensure representative distribution across classes.

5. **Random Forest Classifier:**
   - Created a Random Forest classifier with default properties (n_estimators=100, criterion='gini').

6. **Results:**
   - Achieved an Accuracy Score of 0.78 on the test data.
   - Evaluated the model using a detailed Classification Report and Confusion Matrix.

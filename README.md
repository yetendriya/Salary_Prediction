# Salary_Prediction
# Project Overview
The Salary Prediction Project is a machine learning-based initiative aimed at predicting salaries for freshers based on various attributes such as academic percentages, experience, and other relevant factors.
The project utilizes Python and popular machine learning libraries to process and analyze the data, train predictive models, and make accurate predictions.

# Data Preprocessing and Exploration

Data Cleaning: The project begins by importing the dataset and cleaning it to handle missing values and ensure consistency in the data.
Exploratory Data Analysis (EDA): Exploratory analysis techniques such as histograms, bar plots, and correlation matrices are employed to understand the distribution and relationships among different attributes.
Feature Engineering
Categorical Encoding: Categorical variables like gender, board of education, and specialization are encoded using one-hot encoding to make them suitable for machine learning algorithms.
Total Percentage Calculation: A new feature, total percentage, is created by summing up the percentages from various education levels to capture an overall academic performance measure.

# Model Selection and Training

Random Forest Classifier: The project initially employs the Random Forest Classifier to predict salary placement status. 
Grid search is used to optimize hyperparameters, resulting in an accuracy of approximately 93%.

XGBoost Classifier: The project also utilizes the XGBoost Classifier after feature scaling. The model achieves an impressive accuracy of around 98%, demonstrating its superior predictive power.

# Model Evaluation

Accuracy, Precision, Recall, F1 Score: Multiple metrics such as accuracy, precision, recall, and F1 score are calculated to evaluate the models' performance. These metrics provide a comprehensive understanding of the models' effectiveness in predicting salary placement.

ROC-AUC Score: The ROC-AUC score, a crucial metric for binary classification, is calculated to assess the XGBoost model's ability to distinguish between positive and negative classes.

# Conclusion

The Salary Prediction Project showcases the power of machine learning in predicting salary outcomes for freshers. By employing advanced algorithms and careful feature engineering, the project achieves highly accurate predictions. These predictions can be invaluable for both job seekers and employers, aiding in better decision-making processes during the hiring phase.

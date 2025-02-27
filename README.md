# Customer-Churn-Prediction
Perform customer churn prediction using a RandomForest Classifier on a dataset where the target variable is "Exited"

Here’s a breakdown of the steps I followed:

Loading and Exploring the Data

I loaded the dataset and printed its first few rows to get an overview.
I checked for missing values and dataset structure to ensure data quality.

Data Preprocessing

I standardized column names to lowercase and removed spaces for consistency.
I identified that the correct target column was "Exited" instead of "Churn".
I encoded categorical variables using Label Encoding and applied StandardScaler to numerical features for better model performance.

Splitting the Data

I split the dataset into training (80%) and testing (20%) sets to evaluate model performance properly.
Training the Model

I trained a RandomForest Classifier with 100 decision trees to predict customer churn.
Evaluating the Model

I made predictions on the test set and calculated the accuracy score.
I generated a classification report to assess precision, recall, and F1-score.
I visualized the results using a confusion matrix to understand the model’s classification performance.

Key Findings
- The dataset was preprocessed effectively by encoding categorical variables and normalizing numerical features.
- The RandomForest model performed well, achieving a solid accuracy score.
- The classification report provided detailed insights into model strengths and weaknesses.
- The confusion matrix highlighted any misclassifications, helping to refine future improvements.
- Further enhancements could be made by experimenting with other models, hyperparameter tuning, and feature engineering.

This script serves as a foundational approach to customer churn prediction, with room for further optimization.

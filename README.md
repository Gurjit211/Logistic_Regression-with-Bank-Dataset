1. Load Dataset
Load the bank.csv file.

Remove any rows with missing values.

2. Explore Data
Display dataset shape and column names.

Group basic education levels into a single Basic category for simplicity.

3. Visualize Data
Plot the distribution of the target variable y.

Visualize relationships between y and variables such as job, marital status, education, day_of_week, month, poutcome, and age.

4. Encode Categorical Variables
Convert categorical columns to dummy variables using one-hot encoding.

5. Prepare Training and Testing Sets
Define X (features) and y (target).

Split data into 70% training and 30% testing sets, maintaining class distribution.

6. Handle Class Imbalance
Apply SMOTE to balance the target classes in the training set.

7. Scale Features
Standardize numerical features for optimal model performance.

8. Train Logistic Regression Model
Train a logistic regression model with the training data.

Make predictions on the test data.

Evaluate performance using confusion matrix, classification report, accuracy score, and ROC-AUC score.

9. Feature Selection
Apply Recursive Feature Elimination (RFE) to select the top 20 features.

Drop the least informative feature identified by RFE.

Re-split, re-balance, re-scale, retrain the model, and re-evaluate its performance.

Results
The model achieves an accuracy of 90% and an ROC-AUC score of 0.75, both before and after feature selection, showing stable performance.

Requirements
Python 3.x

pandas

numpy

matplotlib

seaborn

scikit-learn

imbalanced-learn

How to Run
Place bank.csv in the project directory.

Run the Python script or notebook containing the code.

Review generated visualizations and printed evaluation metrics.

Conclusion
This assignment demonstrates an end-to-end pipeline for a classification task, covering key machine learning steps: data cleaning, exploration, balancing, modeling, and feature selection.

# Credit Scoring Model

This project predicts an individual's creditworthiness based on past financial data. It uses classification algorithms such as Logistic Regression, Decision Tree, and Random Forest to classify credit scores as good or bad.

## Dataset
The dataset used is from Kaggle: [Credit Score Dataset](https://www.kaggle.com/datasets/akritiupadhyayks/credit-score-dataset).

Key features include:
- Income, Debt, Credit Limit
- Payment history, Current balance
- Derived features like Debt-to-Income ratio and Credit Utilization

## Steps Followed
1. **Load and Explore Data**: Checked structure, missing values, duplicates, and basic statistics.
2. **Data Cleaning**: Dropped missing values and encoded categorical variables.
3. **Feature Engineering**: Added new features such as Debt-to-Income ratio.
4. **Data Splitting**: Separated features and target, then split into train and test sets.
5. **Feature Scaling**: Standardized numerical features for better model performance.
6. **Model Training**: Trained Logistic Regression, Decision Tree, and Random Forest classifiers.
7. **Model Evaluation**: Evaluated using Accuracy, Precision, Recall, F1-score, ROC-AUC, and confusion matrix.
8. **Model Saving**: Saved the best model (`Random Forest`) for future predictions.

Metrics

Classification Report (Precision, Recall, F1-Score)

ROC-AUC for binary classification

Confusion Matrix visualization

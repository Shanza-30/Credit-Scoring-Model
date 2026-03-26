# 💳 Credit Scoring Model

This project task 1 code alpha predicts an individual's **creditworthiness** based on historical financial data. It applies multiple **classification algorithms** such as **Logistic Regression, Decision Tree, and Random Forest** to classify credit scores as **Good** or **Bad**.

The goal is to evaluate model performance and select the best-performing model for reliable credit risk assessment.


## 📂 Dataset

**Dataset Source:**  
Kaggle – Credit Score Dataset  
🔗 https://www.kaggle.com/datasets/akritiupadhyayks/credit-score-dataset  

### Key Features:
- Income  
- Debt  
- Credit Limit  
- Payment History  
- Current Balance  
- Engineered Features:
  - Debt-to-Income Ratio  
  - Credit Utilization  


## ⚙️ Steps Followed

1. **Load and Explore Data**  
   - Checked dataset structure  
   - Identified missing values and duplicates  
   - Reviewed basic statistical summaries  

2. **Data Cleaning**  
   - Handled missing values  
   - Encoded categorical variables  

3. **Feature Engineering**  
   - Created derived features such as:
     - Debt-to-Income Ratio  
     - Credit Utilization  

4. **Data Splitting**  
   - Separated features and target variable  
   - Split data into training and testing sets  

5. **Feature Scaling**  
   - Standardized numerical features to improve model performance  

6. **Model Training**  
   - Logistic Regression  
   - Decision Tree  
   - Random Forest  

7. **Model Evaluation**  
   - Compared models using multiple evaluation metrics  

8. **Model Saving**  
   - Saved the best-performing model (**Random Forest**) for future predictions  


## 📊 Evaluation Metrics

- **Classification Report**
  - Precision  
  - Recall  
  - F1-Score  

- **ROC-AUC Score** for binary classification  

- **Confusion Matrix Visualization**  

These metrics help assess model accuracy, reliability, and classification performance.


## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  


## 📌 Outcome

This project successfully identifies individuals’ credit risk by comparing multiple machine learning models and selecting the most effective one. It demonstrates a complete ML pipeline from **data preprocessing** to **model evaluation and saving**, making it a practical solution for credit scoring analysis.

---

# Payment Fraud Detection

## 📌 Overview
This project focuses on detecting fraudulent payment transactions using machine learning models. 
It follows a complete data science pipeline — from data preprocessing and exploratory data analysis (EDA) 
to model training, evaluation, and comparison.

## 📂 Dataset
- **File:** `payment_fraud.csv`
- The dataset contains transaction records with features describing payment details and a target variable indicating whether the transaction was fraudulent.

## 🚀 Approach
1. **Data Import & Cleaning**
   - Loaded dataset and handled missing values.
   - Converted categorical variables into numerical format.
   - Performed scaling where necessary.

2. **Exploratory Data Analysis (EDA)**
   - Visualized feature distributions.
   - Identified correlations between variables.
   - Checked class imbalance.

3. **Model Training**
   - Implemented and compared multiple models:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - K-Nearest Neighbors (KNN)

4. **Model Evaluation**
   - Used `accuracy_score` as the primary evaluation metric.
   - Compared performance across models.


## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## ▶️ Usage
```bash
# Run the Jupyter Notebook
jupyter notebook Payment_Fraud.ipynb
```

## 📌 Future Improvements
- Implement more advanced models (XGBoost, LightGBM).
- Use SMOTE or similar techniques for class imbalance.
- Deploy the model as a web service.

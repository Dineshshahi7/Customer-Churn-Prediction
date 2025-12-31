Title: Customer Churn Prediction using Machine Learning

# Project Overview
Customer churn refers to customers who stop using a company’s services.  
This project aims to "predict customer churn" using machine learning techniques so that businesses can take preventive actions to retain customers.

The model is trained on a real-world "telecom customer dataset" and evaluates different machine learning algorithms to find the best-performing model.

# Problem Statement
Telecom companies face significant revenue loss due to customer churn.  
Manually identifying customers who are likely to leave is difficult and inefficient.

The objective of this project is to:
- Predict whether a customer will churn or not
- Identify important factors that influence churn
- Help businesses improve customer retention strategies


# Solution Approach
The solution follows a complete machine learning pipeline:
1. Data loading and understanding  
2. Data cleaning and preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature encoding and scaling  
5. Model training  
6. Model evaluation and comparison  


# Dataset Information
- **Dataset Name:** Telecom Dataset  
- **Source:** Kaggle  
- **Target Variable:** Churn (Yes / No)

The dataset includes:
- Customer demographics  
- Account information  
- Service usage details  

Missing values and categorical features were handled during preprocessing.

---

# Tools & Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib & Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

# Machine Learning Models Used
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  

Each model was trained and evaluated to compare performance.

---

# Model Evaluation
Models were evaluated using:
- Accuracy  
- Confusion Matrix  
- Classification Report  

✅ **Logistic Regression** performed best with approximately **81% accuracy** on test data.

---

# Key Insights
- Shorter tenure customers are more likely to churn compared to long-term customers, indicating loyalty reduces churn risk.
- Month-to-month contract customers have the highest churn probability, while fixed contracts (1 or 2 years) show better retention. 
- Higher monthly charges correlate with higher churn, indicating price sensitivity among customers.
- Feature importance analysis shows that tenure, contract type, monthly charges, and total charges are among the top predictors of churn.

---

# How to Run the Project

This project has been deployed as an interactive web application using Hugging Face Spaces.

You can directly access and test the model here:
🔗 Live Demo: https://huggingface.co/spaces/dineshshahi/Customer_churn_prediction

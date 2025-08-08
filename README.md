![image](https://github.com/muhammadrehanazam/Credit_card_approvals/blob/main/credit_card.jpg)
# Credit Card Approval Prediction

This project predicts **credit card approvals** using **Supervised Machine Learning** techniques, specifically **Logistic Regression** with hyperparameter tuning via GridSearchCV.  
The model is trained and tested on a dataset containing various applicant details, and the goal is to determine whether a credit card application should be **approved** or **denied**.

---

## 📌 Project Overview
Banks and financial institutions receive thousands of credit card applications daily.  
Manually reviewing these applications is **time-consuming** and prone to **human bias**.  
This project automates the decision-making process using **machine learning**, ensuring:
- Faster decisions  
- Improved accuracy  
- Reduced manual workload  

---

## ⚙️ Features of the Model
- **Data Preprocessing**  
  - Handles categorical (`object`) and numerical (`int`, `float`) data  
  - Scales features using `StandardScaler` for better model performance  
  - Converts column names to strings to avoid indexing issues  

- **Machine Learning Model**  
  - Logistic Regression from `scikit-learn`  
  - Hyperparameter tuning using `GridSearchCV` to find the best `C`, `solver`, and `max_iter`  
  - 5-fold cross-validation for reliable results  

- **Model Evaluation**  
  - Accuracy score on the test set  
  - Confusion Matrix to analyze prediction performance  

---

## 🛠 Technologies Used
- **Python 3.x**  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical computations  
- **Scikit-learn** – ML models & preprocessing  
- **GridSearchCV** – Hyperparameter optimization
  

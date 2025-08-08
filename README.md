![image]([C:\Users\DIWANs\Downloads\workspace\workspace](https://www.google.com/imgres?q=credit%20card%20approvals&imgurl=https%3A%2F%2Fcamo.githubusercontent.com%2Fd73f492c839b63b0a58cef41a1cb292574911d6ae626ebb1526a33cc17aeed6d%2F68747470733a2f2f63646e2e676f62616e6b696e6772617465732e636f6d2f77702d636f6e74656e742f75706c6f6164732f323031362f30372f6973746f636b5f32313937303436365f6c617267652d322e6a7067&imgrefurl=https%3A%2F%2Fgithub.com%2FSayamAlt%2FCredit-Card-Approval-Prediction&docid=9wOTiD5gNm5thM&tbnid=LNGOMJMrdAtEwM&vet=12ahUKEwiTm6WtwvqOAxXy87sIHSCaHIkQM3oECCAQAA..i&w=2200&h=1376&hcb=2&ved=2ahUKEwiTm6WtwvqOAxXy87sIHSCaHIkQM3oECCAQAA))
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
  

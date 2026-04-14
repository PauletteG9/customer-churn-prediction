# 📊 Customer Churn Prediction using Random Forest

This project focuses on predicting customer churn using a **Random Forest Classifier**. It helps businesses identify customers who are likely to leave, enabling better retention strategies.

---

## 🚀 Project Overview

Customer churn is a major problem for businesses. This project uses machine learning to analyze customer data and predict whether a customer will churn based on features like:

- Tenure
- Monthly Charges
- Total Charges
- Number of Services
- Contract Type
- Payment Method
- Tech Support
- Online Security
- Senior Citizen

---

## 🧠 Model Used

- **Random Forest Classifier**
- Criterion: Gini Index
- Number of Trees: 100

---

## 📈 Model Performance

| Metric        | Value |
|--------------|------|
| Accuracy     | 63%  |
| Precision    | 64.22% |
| Recall       | 66.67% |
| F1 Score     | 65.42% |
| ROC-AUC      | 69.70% |

---

## 📊 Visualizations

The project includes:
- Churn Distribution
- Feature Importance
- Confusion Matrix
- ROC Curve

---

## 🔍 Key Insights

- **Monthly Charges** and **Total Charges** are the most important features
- Customers with **low tenure and high charges** are more likely to churn
- Contract type significantly affects churn behavior

---

## ⚙️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Project Structure
customer-churn-prediction/

│── CustomerChurnPrediction.ipynb

│── churn_model_results.png

│── README.md

│── requirements.txt


---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/customer-churn-prediction.git
Navigate to the folder:
cd customer-churn-prediction
Install dependencies:
pip install -r requirements.txt
Run the notebook:
jupyter notebook

🎯 Use Cases
Customer retention strategies
Telecom / subscription business analysis
Predictive analytics applications

🔮 Future Improvements
Hyperparameter tuning
Try advanced models (XGBoost, LightGBM)
Deploy as a web app (Flask/Streamlit)

👤 Author : Paulette Gudapati
This project was done as part of Mtech Coursework

⭐ If you found this useful, consider giving it a star!

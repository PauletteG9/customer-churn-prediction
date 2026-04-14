# 📊 Customer Churn Prediction using Random Forest

This project focuses on predicting customer churn using a **Random Forest Classifier**. It helps businesses identify customers who are likely to leave, enabling better retention strategies through data-driven insights.

---

## 🚀 Project Overview

Customer churn is a major challenge for businesses. This project applies machine learning techniques to analyze customer data and predict whether a customer will churn based on features such as:

* Tenure
* Monthly Charges
* Total Charges
* Number of Services
* Contract Type
* Payment Method
* Tech Support
* Online Security
* Senior Citizen

---

## 🧠 Model Used

* **Random Forest Classifier**
* Criterion: Gini Index
* Number of Trees: 100

---

## 📈 Model Performance

| Metric    | Value  |
| --------- | ------ |
| Accuracy  | 63%    |
| Precision | 64.22% |
| Recall    | 66.67% |
| F1 Score  | 65.42% |
| ROC-AUC   | 69.70% |

---

## 📊 Visualizations

The project includes the following visual insights:

* Churn Distribution
* Feature Importance Ranking
* Confusion Matrix
* ROC Curve

---

## 🔍 Key Insights

* **Monthly Charges** and **Total Charges** are the most influential features
* Customers with **low tenure and high charges** are more likely to churn
* Contract type plays a significant role in customer retention

---

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📂 Project Structure

customer-churn-prediction/
│── CustomerChurnPrediction.ipynb

│── churn_model_results.png

│── README.md

│── requirements.txt

---

## ▶️ How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/YOUR_USERNAME/customer-churn-prediction.git
   ```

3. Navigate to the project folder
   ```bash
   cd customer-churn-prediction
   ```

5. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

7. Run the notebook
   ```bash
   jupyter notebook
   ```

---

## 🎯 Use Cases

* Customer retention strategy development
* Telecom and subscription-based business analysis
* Predictive analytics applications

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Experiment with advanced models (XGBoost, LightGBM)
* Deploy as a web application using Flask or Streamlit

---

## 👤 Author

**Paulette Gudapati**

---

⭐ If you found this project useful, consider giving it a star!

---

This project was done as part of MTech coursework

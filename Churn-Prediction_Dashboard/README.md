# 📊 Customer Churn Prediction with Tableau Dashboard

This project leverages machine learning and explainable AI techniques to predict customer churn and present insights through an interactive Tableau dashboard. It helps identify at-risk customers and offers actionable recommendations for improving customer retention.

---

## 🔍 Objective

The primary goal is to classify customers who are likely to churn based on historical data, understand key factors driving churn using SHAP explainability, and visualize the results using Tableau for business stakeholders.

---

## 🧠 Machine Learning Workflow

- Preprocessing customer demographic and service data
- Feature encoding and scaling
- Training baseline and tuned models (Logistic Regression, Random Forest)
- Evaluation using Accuracy, Precision, Recall, and F1-Score
- Model interpretation with SHAP values

---

## 📈 Key Results

- **Model Used**: Random Forest (Tuned)
- **Accuracy**: 77.00%
- **F1 Score (Churn)**: 63.35%
- **Precision (Churn)**: 54.90%
- **Recall (Churn)**: 74.87%

---

## 🧾 Tableau Dashboard

The dashboard includes:
- Global SHAP Feature Importances
- Confusion Matrix
- KPI Summary of model performance

![Churn Dashboard](./Churn%20Analysis%20Dashboard.png)

🔗 **Tableau Public**: https://public.tableau.com/views/ChurnAnalysis_17482925314010/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## 📂 Project Structure
📁 Churn-Prediction-Dashboard/
├── Customer_Churn_prediction_project.ipynb
├── Churn Analysis Dashboard.png
├── README.md

---

## 💡 Tools Used

- **Python**: pandas, sklearn, shap, matplotlib
- **Tableau**: Dashboard for SHAP visualizations and KPIs
- **Jupyter Notebook**: For model development and EDA

---

## 🚀 How to Run

1. Clone this repository: git clone https://github.com/yourusername/Churn-Prediction-Dashboard.git
cd Churn-Prediction-Dashboard
2. Open the notebook: jupyter notebook Customer_Churn_prediction_project.ipynb
3. View the Tableau dashboard using the public link above.

---

## 🤝 Let's Connect

- **LinkedIn**: https://www.linkedin.com/in/apadmanabhan98/
- **Email**: apadmanabhan@ucdavis.edu

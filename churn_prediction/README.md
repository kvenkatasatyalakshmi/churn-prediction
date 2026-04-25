# 📊 Customer Churn Analysis & Prediction

## 🔍 Objective
Analyze customer behavior and predict churn to help businesses improve retention and reduce customer loss using data-driven insights.

---

## 📌 Problem Statement
Customer churn is a major challenge in subscription-based businesses. Identifying customers likely to leave enables proactive retention strategies and improves business performance.

---

## 🔄 Data Processing (ETL Pipeline)
- Extracted raw telecom customer dataset
- Transformed data by cleaning missing values and correcting inconsistencies
- Loaded processed data for analysis and modeling
- Removed irrelevant columns (customerID)
- Converted TotalCharges to numeric format
- Handled missing values using median imputation

---

## 📊 Exploratory Data Analysis (EDA)
- Analyzed churn distribution across customer segments
- Identified patterns between churn and contract type
- Studied impact of monthly charges on churn behavior
- Discovered high-risk customer groups

---

## ⚙️ Feature Engineering
- Encoded categorical variables using one-hot encoding
- Scaled numerical features for model performance

---

## 🤖 Model Building
- Logistic Regression (Baseline Model)
- Artificial Neural Network (ANN)

---

## 📈 Evaluation Results
- Model Accuracy: ~81%
- Evaluated using:
  - Confusion Matrix
  - Precision, Recall, F1-score

---

## 🔍 Key Insights
- Month-to-month contract customers show highest churn rate
- Higher monthly charges increase likelihood of churn
- Long-term contracts significantly reduce churn probability
- Payment method influences customer retention behavior

---

## 📌 Business Impact
- Helps identify high-risk customers for targeted retention strategies
- Supports decision-making for marketing and customer engagement teams
- Improves operational efficiency by reducing churn-related revenue loss

---

## 🧠 Recommendations
- Promote long-term subscription plans
- Offer discounts to high-risk high-charge customers
- Improve service experience for at-risk segments
- Focus retention campaigns on month-to-month users

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy)
- Data Visualization (Matplotlib, Seaborn)
- Machine Learning (Scikit-learn)
- Deep Learning (TensorFlow / Keras)

---

## 🚀 Outcome
Built a predictive churn model and extracted actionable insights to support business decision-making and improve customer retention strategies.

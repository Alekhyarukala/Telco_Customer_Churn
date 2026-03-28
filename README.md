# 📊 Customer Retention & Churn Analysis

## 🚀 Project Overview

Customer churn is one of the most critical challenges for subscription-based businesses. This project analyzes customer behavior using telecom data to identify churn patterns, understand retention drivers, and provide actionable business recommendations.

---

## 🎯 Objectives

* Analyze overall churn rate and retention trends
* Identify high-risk customer segments
* Study customer lifetime behavior
* Perform cohort analysis to understand churn over time
* Provide data-driven recommendations to improve retention

---

## 📁 Dataset

This project uses the **Telco Customer Churn Dataset** from Kaggle.

* 🔗 Source: https://www.kaggle.com/datasets/blastchar/telco-customer-churn
* 🏢 Domain: Telecommunications
* 👥 Total Customers: **7044**

### 📌 Dataset Includes:

* Customer demographics
* Subscription details (contract type, tenure)
* Services used (internet, streaming, tech support)
* Billing & payment methods
* Churn status (Yes/No)

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

## 🧹 Data Preparation

* Converted `TotalCharges` to numeric format
* Handled missing values
* Created `Churn_Num` (1 = churn, 0 = retained)
* Created `tenure_group` for cohort analysis

---

## 📊 Key Analysis

### 🔹 Overall Churn Rate

* **26.5%** of customers have churned

---

### 🔹 Customer Segmentation Insights

#### 📌 Contract Type

* Month-to-month → highest churn
* Long-term contracts → significantly lower churn

#### 📌 Payment Method

* Electronic check → **~45% churn (highest risk)**
* Automatic payments → lowest churn

#### 📌 Internet Service

* Fiber optic → **~42% churn**
* DSL → moderate churn
* No internet → lowest churn

#### 📌 Tech Support

* No support → **~41% churn**
* With support → much lower churn

---

### 🔹 Customer Lifetime Analysis

* Churn is highest in the early stages
* Long-term customers show strong retention

---

### 🔹 Cohort Analysis (Tenure-Based)

| Tenure Group | Churn Rate |
| ------------ | ---------- |
| 0–12 months  | 47.7%      |
| 12–24 months | 28.7%      |
| 24–48 months | 20.3%      |
| 48+ months   | 9.5%       |

---

## 🔍 Key Insights

* Nearly **50% of customers churn within the first year**
* Early-stage retention is the most critical challenge
* Short-term contracts drive higher churn
* Manual payment methods increase churn risk
* Lack of tech support significantly impacts retention
* Customer loyalty increases with tenure

---

## ⚠️ Key Churn Drivers

* Month-to-month contracts
* No tech support
* Electronic check payment method
* Fiber optic service users
* Poor onboarding experience

---

## 💡 Recommendations

* Encourage long-term subscriptions through incentives
* Promote automatic payment methods
* Improve onboarding (first 3 months critical)
* Provide better and proactive tech support
* Target high-risk segments with retention campaigns

---

## 📈 Visualizations

The project includes:

* Churn by Contract Type
* Churn by Payment Method
* Churn by Internet Service
* Cohort Analysis (Tenure Groups)

---

## 📌 Conclusion

Churn is highly influenced by early customer experience, service quality, and engagement level. By focusing on high-risk segments and improving onboarding and support, businesses can significantly enhance customer retention.

---

## 🔗 Project Files

* `Telco_Customer_Churn.ipynb`
* Dataset (CSV)
* Visualizations

---

## 👩‍💻 Author

**Alekhya Rukala**
Aspiring Data Analyst 

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

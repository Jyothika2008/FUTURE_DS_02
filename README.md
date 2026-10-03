# FUTURE_DS_02 — Customer Churn Analysis

## 📊 Project Overview

This project focuses on analyzing customer churn in a telecommunications dataset to understand customer retention, identify churn patterns, and explore the factors associated with customer churn.

The analysis was completed as part of **Future Interns — Data Science & Analytics Task 2**.

The project includes data cleaning, statistical analysis, churn comparisons, visualizations, and a professional customer churn dashboard created using Python.

---

## 🎯 Objective

The main objectives of this analysis are to:

- Analyze overall customer churn and retention.
- Identify patterns in customer churn.
- Compare churn across different contract types.
- Analyze customer churn based on tenure.
- Compare monthly charges between churned and retained customers.
- Analyze churn across internet service types.
- Analyze churn across payment methods.
- Examine the relationship between technical support and churn.
- Explore customer characteristics such as senior citizen status, gender, partner status, and dependent status.
- Present the findings through a professional dashboard.

---

## 📁 Dataset

The project uses the **Telco Customer Churn dataset** containing customer information related to:

- Customer ID
- Gender
- Senior Citizen status
- Partner
- Dependents
- Tenure
- Phone Service
- Multiple Lines
- Internet Service
- Online Security
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Contract
- Paperless Billing
- Payment Method
- Monthly Charges
- Total Charges
- Churn

The dataset contains **7,043 customer records** and **21 columns**.

---

## 🧹 Data Preparation

The following data preparation steps were performed:

- Checked the dataset structure and columns.
- Checked for missing values.
- Converted `TotalCharges` into a numeric format.
- Identified missing values in `TotalCharges`.
- Checked for duplicate records.
- Prepared the data for churn analysis.
- Created tenure groups for customer lifetime analysis.

---

## 📈 Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Customers | 7,043 |
| Customers Retained | 5,174 |
| Customers Churned | 1,869 |
| Retention Rate | 73.46% |
| Churn Rate | 26.54% |

---

## 🔍 Analysis Performed

### 1. Churn Distribution

Customer churn was analyzed to understand the overall distribution of retained and churned customers.

- Customers retained: **5,174**
- Customers churned: **1,869**
- Retention rate: **73.46%**
- Churn rate: **26.54%**

### 2. Churn by Contract Type

Churn was compared across different contract types.

| Contract Type | Churn Rate |
|---|---:|
| Month-to-month | 42.71% |
| One year | 11.27% |
| Two year | 2.83% |

Month-to-month customers had the highest observed churn rate.

### 3. Churn by Tenure

Customer tenure was analyzed to understand how churn varies with customer lifetime.

Customers were grouped into:

- 0–12 months
- 13–24 months
- 25–48 months
- 49–72 months

| Tenure Group | Churn Rate |
|---|---:|
| 0–12 months | 47.44% |
| 13–24 months | 28.71% |
| 25–48 months | 20.39% |
| 49–72 months | 9.51% |

The analysis shows that the observed churn rate was higher among customers with shorter tenure.

### 4. Monthly Charges vs Churn

Average monthly charges were compared between retained and churned customers.

| Churn Status | Average Monthly Charges |
|---|---:|
| No | 61.27 |
| Yes | 74.44 |

Customers who churned had higher average monthly charges in this dataset.

### 5. Internet Service vs Churn

Churn was compared across internet service types.

| Internet Service | Churn Rate |
|---|---:|
| DSL | 18.96% |
| Fiber optic | 41.89% |
| No internet service | 7.40% |

Fiber optic customers had the highest observed churn rate.

### 6. Payment Method vs Churn

Churn was analyzed across different payment methods.

The highest observed churn rate was among customers using **Electronic check**, at **45.29%**.

### 7. Tech Support vs Churn

The relationship between technical support and churn was analyzed.

| Tech Support | Churn Rate |
|---|---:|
| No | 41.64% |
| Yes | 15.17% |
| No internet service | 7.40% |

Customers without technical support showed a higher observed churn rate.

### 8. Customer Characteristics

Additional comparisons were performed using:

- Senior Citizen status
- Gender
- Partner status
- Dependents status

Senior citizens had an observed churn rate of **41.68%**, compared with **23.61%** for non-senior customers.

Gender showed only a small difference in observed churn rates.

---

## 💡 Key Business Insights

The analysis identified several customer groups with higher observed churn rates:

- Month-to-month customers.
- Customers with shorter tenure.
- Fiber optic customers.
- Electronic-check users.
- Customers without technical support.
- Senior citizens.
- Customers with higher average monthly charges.

These patterns can help businesses identify customer segments that may require closer attention and targeted retention strategies.

---

## 📊 Dashboard

A professional **Customer Churn Analysis Dashboard** was created to present the analysis visually.

The dashboard includes:

- Customer churn distribution
- Churn rate
- Retention rate
- Churn by contract type
- Churn by tenure
- Monthly charges vs churn
- Internet service vs churn
- Payment method vs churn
- Tech support vs churn
- Customer demographic analysis
- Key business insights

The dashboard is designed to provide a clear overview of customer churn and allow the analysis to be understood quickly.

---

## 🛠️ Tools Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Plotly**
- **Google Colab / Jupyter Notebook**

---

## 📂 Project File

The main analysis notebook is:

`FUTURE_DS_Task_02_Customer_Churn_Analysis.ipynb`

---

## 🎓 Internship

**Program:** Future Interns  
**Track:** Data Science & Analytics  
**Task:** Task 2 — Customer Churn Analysis

---

## 👩‍💻 Author

**Jyothika J.**

Currently pursuing B.Tech in Computer Science and Engineering with specialization in Data Science

# Customer_churn_data_analysis

# Customer Churn Analysis Project

## 📌 Project Overview

Customer churn refers to the percentage of customers who stop using a company’s products or services during a specific time period. Retaining existing customers is often more cost-effective than acquiring new ones, making churn analysis a critical business problem.

This project focuses on analyzing customer churn using exploratory data analysis (EDA) techniques. The goal is to identify patterns, trends, and key factors that influence customer churn and to derive actionable insights that can help improve customer retention strategies.

---

## 📊 Objectives of the Project

* Analyze customer churn distribution and overall churn rate
* Identify key factors influencing churn behavior
* Understand the impact of services, contracts, and payment methods on churn
* Visualize insights using meaningful charts and graphs
* Provide business-oriented recommendations based on data analysis

---

## 📁 Dataset Description

* **Dataset Name:** Customer Churn Dataset
* **File Used:** `Customer Churn.csv`
* **Source:** Publicly available telecom churn dataset
* **Size:** Contains customer-level records with demographic, service, and billing details

### 🔑 Key Features in the Dataset

* **Demographic Information:** Gender, Senior Citizen status
* **Service Details:** Phone service, Internet service, Online security, Backup, Tech support, Streaming services
* **Contract Information:** Contract type (Month-to-month, One year, Two year)
* **Payment Details:** Payment method, Monthly charges, Total charges
* **Target Variable:** `Churn` (Yes / No)

---

## 🛠️ Tools & Technologies Used

* **Programming Language:** Python
* **Libraries:**

  * Pandas – data manipulation and analysis
  * NumPy – numerical operations
  * Matplotlib & Seaborn – data visualization
* **Environment:** Jupyter Notebook

---

## 🔍 Data Preprocessing Steps

* Loaded the dataset using Pandas
* Checked for missing and null values
* Converted categorical values into appropriate formats
* Ensured data consistency and correctness
* Verified data types for numerical and categorical columns

---

## 📈 Exploratory Data Analysis (EDA)

The following analyses and visualizations were performed:

### 1️⃣ Overall Churn Distribution

* Calculated overall churn rate
* **26.54% of customers churned**, while **73.46% remained active**
* Visualized churn distribution using bar and pie charts

### 2️⃣ Demographic Analysis

* Analyzed churn by gender
* Found nearly equal churn contribution from male and female customers
* Concluded demographics alone are not strong churn predictors

### 3️⃣ Service Usage Analysis

* Evaluated churn impact based on internet service types
* **Fiber optic users showed the highest churn (~42%)**
* Customers without value-added services had significantly higher churn

**Key Observations:**

* Over **60% of churned customers lacked online security**
* Nearly **64% of churned customers did not use tech support**
* Customers with multiple services were more engaged and less likely to churn

### 4️⃣ Contract Type Analysis

* **Month-to-month contracts accounted for over 88% of churn**
* Long-term contracts (1-year and 2-year) showed much lower churn

### 5️⃣ Payment Method Analysis

* **Electronic check users contributed ~45% of total churn**
* Customers using automatic payment methods had better retention

---

## 📊 Visualizations

The project includes multiple visualizations such as:

* Bar charts for churn comparison
* Pie charts for percentage distribution
* Count plots for service usage
* Comparative charts for contract and payment analysis

These charts help in clearly understanding churn patterns and trends.

---

## 📌 Key Insights

* Churn rate is significantly influenced by service engagement
* Customers with fewer subscribed services are more likely to churn
* Payment convenience plays a critical role in retention
* Long-term contracts greatly reduce churn probability

---

## 💡 Business Recommendations

* Encourage customers to opt for long-term contracts through incentives
* Promote bundled service packages (security, backup, tech support)
* Motivate users to switch to automated payment methods
* Focus retention strategies on high-risk segments such as fiber optic and month-to-month users

---

## 📂 Project Structure

```
Customer-Churn-Analysis/
│
├── Customer Churn.csv          # Dataset file
├── Customer_churn.ipynb        # Jupyter Notebook with analysis
├── README.md                   # Project documentation
```

---

## 🚀 Conclusion

This customer churn analysis provides valuable insights into customer behavior and highlights actionable areas to improve retention. By leveraging data-driven strategies focused on service value, payment methods, and contract types, organizations can significantly reduce churn and enhance customer satisfaction.

---

## 📬 Contact

For any questions or suggestions related to this project, feel free to reach out.

**Author:** Sanmitha S. Shetty

# 📉 Bank Customer Churn Analysis Dashboard (Power BI)

This project is a dedicated **Data Analysis** solution focused on identifying the key drivers that cause bank customers to leave (Churn). It demonstrates skills in **statistical analysis**, **predictive modeling concepts**, and deriving strategic recommendations.

---

## Project Goal
To design an **interactive Power BI dashboard** that pinpoints the demographic, financial, and behavioral factors that highly correlate with customer churn (Exited = 1). The goal is to provide bank management with **actionable insights** to develop targeted retention strategies.

## Key Features
* **Churn Rate Tracking:** Monitoring the overall customer exit rate (Exited) across different segments.
* **Geographic Analysis:** Comparing churn rates and customer loyalty across countries (France, Spain, Germany).
* **Feature Correlation:** Visualizing the relationship between churn and key variables like **Credit Score**, **Balance**, **Age**, and **Active Member Status**.

## 🛠 Technology & Methodology
* **BI Tool:** **Power BI** (Used for Dashboard Development, Data Visualization, and DAX calculations).
* **Data Source:** `Bank_Churn.csv` (Contains 10,000 customer records with 13 features).
* **Data Preparation:** Used **Power Query** to clean the data and ensure all features are correctly mapped according to the provided data dictionary.
* **Statistical Analysis:** Applied **segmentation analysis** and **correlation metrics** within Power BI to identify high-risk customer groups—a foundation for predictive modeling.

---

## Key Findings (Strategic Insights)

The analysis highlighted critical factors influencing customer churn:

* **Inactivity and Churn:** Customers who are **Not Active Members (IsActiveMember = 0)** showed a significantly higher churn rate compared to active members.
* **Geographic Risk:** The churn rate in **Germany** is notably higher than in other regions, suggesting localized market issues or competitive pressure.
* **Balance and Products:** Churn is notably higher among customers who hold a High Account Balance but utilize a Low Number of Products (primarily one). This indicates that customers with significant assets are not fully engaged with the bank, suggesting a critical gap in personalized cross-selling or wealth management strategies.
* **Age as a Driver:** The highest concentration of churn occurs within the 35-60 bracket, requiring immediate targeted retention campaigns.

---

## Deliverables
* **PBIX File:** The complete Power BI report file (`BankCustomerChurn.pbix`).
* **Data Source:** The raw dataset used for analysis (`Bank_Churn.csv`).
## Project Relevance
This project perfectly aligns with the required skills, demonstrating expertise in **Data Analytics** and providing a practical application of **Statistical Analysis** and the fundamentals of **Predictive Modeling**.

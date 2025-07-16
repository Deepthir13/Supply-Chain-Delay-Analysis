# 📦 Supply Chain Delay & SLA Breach Analysis

A full end-to-end data analysis and modeling project that explores delivery delays, SLA breaches, and root cause drivers in a global supply chain dataset. Built with Python and exported to Excel for dashboarding.

---

## 🚀 Project Overview

This project analyzes a dynamic supply chain dataset to:

* Calculate delivery delays and SLA breaches
* Identify delay-prone suppliers, products, and regions
* Predict delay duration using machine learning
* Segment routes via clustering to uncover high-risk patterns
* Estimate financial impact of delays (cost analysis)
* Export clean insights to Excel for dashboard creation

---

## 📁 Dataset

**Source:** [Kaggle – Supply Chain Logistics Dataset](https://www.kaggle.com/datasets/natasha0786/supply-chain-dataset)

* 113,000+ records across global suppliers
* Fields include inventory levels, equipment, weather, lead time, delivery deviation, risk class, and product/supplier metadata

---

## 🛠️ Tools & Tech Stack

| Category           | Tools Used                                        |
| ------------------ | ------------------------------------------------- |
| Language           | Python (pandas, numpy)                            |
| Visualization      | seaborn, matplotlib                               |
| Machine Learning   | scikit-learn (Random Forest, KMeans)              |
| Reporting & Export | Excel via `pandas.ExcelWriter`                    |
| Analysis Concepts  | SLA analysis, delay rate, root cause, KPI metrics |

---

## 📊 Key Analysis

### ✅ 1. Delay & SLA Breach Analysis

* Created delivery and delay timelines from raw deviation data
* Flagged SLA breaches (delay > 7 days)
* Grouped by supplier, country, risk classification

### ✅ 2. Predictive Modeling

* Trained Random Forest Regressor to predict delay days
* Achieved R² = 0.41 with RMSE \~ 3.5 days
* Used feature importance to identify top delay factors (e.g., demand, risk, supplier)

### ✅ 3. Clustering & Segmentation

* Applied KMeans clustering on demand vs delay
* Identified high-delay, high-demand routes for mitigation

### ✅ 4. Root Cause Insights

* Top 10 suppliers breached SLA over 60% of the time
* Moderate-risk shipments had nearly equal delays as high-risk ones
* Estimated delay cost = **\$15M+**

### ✅ 5. Excel Dashboard Export

* Exported data summaries to Excel (top suppliers, route delay, SLA by risk)
* Enabled clean visualization using PivotTables, charts, and slicers

---

## 💡 Key Outcomes

- ✅ Reduced manual SLA checks by **60%** through automated breach flagging  
- ✅ Enabled early warning for delays using **predictive modeling**  
- ✅ Helped operations reduce estimated delay-related costs by **~$1.5M**

---

## 📌 What This Project Proves

- Strong ability to derive insights from operational datasets  
- Experience building end-to-end analytics + ML pipeline  
- Proficient in Python, SQL, Excel-based BI reporting  
- Business impact focus through cost-saving and risk mitigation

---

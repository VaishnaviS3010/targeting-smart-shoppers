
# 🛍️ Mall Customer Segmentation using KMeans Clustering

## 📌 Problem Statement
Identify the most important customer groups based on **age**, **annual income**, and **spending score** to help the marketing team plan more targeted strategies.

## 🎯 Objective
- Segment mall customers into meaningful groups.
- Determine the ideal number of clusters using the Elbow Method.
- Analyze and visualize the characteristics of each cluster.

---

## 🧠 Context
A retail mall chain has demographic and spending data from its customer base. The marketing team wants to understand different shopping patterns and allocate budget to the most profitable groups. This project focuses on:
- Customer segmentation using unsupervised learning (KMeans).
- Identifying clusters in univariate, bivariate, and multivariate dimensions.
- Visualizing these segments for strategic insights.

---

## 📁 Dataset
The dataset used is the publicly available **Mall Customer Segmentation Data**, containing the following features:
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1–100)`

---

## 🛠️ Tools & Libraries
- Python (Pandas, Seaborn, Matplotlib)
- Scikit-learn (`KMeans`, `StandardScaler`)

---

## 🔍 Workflow

### 1. **Exploratory Data Analysis (EDA)**
- **Distplots** and **KDE plots** were used to visualize feature distributions and compare them across groups (e.g., gender-based income patterns).
- **Scatterplots** explored the relationship between income and spending.
- **Heatmaps** revealed correlations between features to inform clustering choices.

### 2. **Clustering Strategy**
- **Univariate Clustering**: Based on a single feature (e.g., income) to understand basic groupings and set a baseline.
- **Bivariate Clustering**: Used income and spending score together to reveal actionable customer segments.
- **Multivariate Clustering**: Combined age, income, and spending score for deeper, more nuanced segmentation.

> 📌 The Elbow Method was used in all cases to determine the optimal number of clusters.

---

## 📈 Key Findings
- Bivariate clustering revealed **5 meaningful customer segments**, such as:
  - High income, high spenders (ideal targets)
  - High income, low spenders (conversion opportunities)
  - Low income, high spenders (loyal but price-sensitive)
- Multivariate clustering refined these groups further by accounting for **age**, which may affect purchasing capacity and brand preferences.

---

## 💡 Recommendations
- Focus marketing efforts on **Cluster with high spending & income**.
- Offer personalized deals to **low spending but high income** groups to boost engagement.
- Design loyalty programs for **moderate income, high spending** customers.


## 📣 Author Note

This project was completed as part of a **guided project** to learn and apply KMeans clustering to real-world retail customer data. It demonstrates practical applications of unsupervised learning for marketing analytics and customer segmentation.


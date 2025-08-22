# Task 2: Customer Segmentation

## 📌 Objective
Working with **unlabeled mall customer data**, I applied clustering algorithms to divide customers into **five meaningful segments** based on their **Age, Annual Income, and Spending Score**.

## 📂 Dataset
- **Source**: [Mall Customers Dataset (Kaggle)](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)  
- Key features:  
  - `Age`  
  - `Annual Income (k$)`  
  - `Spending Score (1–100)`

## 🔄 Project Pipeline
1. **Data Preparation & EDA** – Explored the dataset to understand distributions and relationships.  
2. **Clustering Models** – Applied multiple clustering algorithms and used **Silhouette Score** to evaluate performance.  
3. **Cluster Naming** – Analyzed characteristics of each group and assigned intuitive names:  
   - 🟦 **Cautious Wealthy** → High income, low spending  
   - 🟩 **Moderate Customers** → Average income & spending  
   - 🟨 **Luxury Spenders** → High income, high spending  
   - 🟧 **Impulsive Shoppers** → Low income, high spending  
   - 🟥 **Budget-Conscious** → Low income, low spending  
4. **Dashboard Creation** – Built an **interactive Power BI dashboard** to visualize and compare customer behaviors across clusters.  

## 📊 Results
- Identified **5 distinct customer groups** with clear behavioral patterns.  
- Dashboard enables quick exploration of segment characteristics.  

## 🛠️ Tools & Libraries
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)  
- K-Means Clustering  
- Power BI (for interactive dashboard)  

## 📎 Files
- `clustering-analysis-of-mall-customers.ipynb`: Main notebook with clustering workflow  
- `Clusterd_Mall_Customers.csv`: Output file with assigned clusters (used in Power BI)  
- `dashboard/`: Power BI file for visualization  
- `Mall_Customers`: Dataset (optional or link in README)  
---
🔗 *Part of my [Elevvo](https://elevvo.tech/) Internship Projects*

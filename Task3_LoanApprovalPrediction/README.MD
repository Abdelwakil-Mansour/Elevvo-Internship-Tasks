# Task 3: Loan Approval Prediction

## 📌 Project Overview
This project focuses on predicting whether a **loan application will be approved** based on applicant details.  
It was designed as a **classification problem**, and multiple ML models were tested to find the best performer.  
Additionally, I experimented with **Orange Data Mining** to build a visual workflow for the same task.

## 📂 Dataset
- **Source**: [Loan Approval Prediction Dataset (Kaggle)](https://www.kaggle.com/datasets/architsharma01/loan-approval-prediction-dataset)  
- Features include applicant income, education, loan amount, credit history, and more.  
- Target variable: **Loan_Status** (Approved / Not Approved)

## 🔄 Project Pipeline
1. **Data Cleaning** – Handled missing values and ensured data consistency.  
2. **Feature Engineering** – Encoded categorical variables for ML models.  
3. **Model Training & Evaluation** – Trained multiple classification algorithms.  
4. **Workflow Visualization** – Used **Orange Data Mining** to replicate and visualize the process.  

## 📊 Results
| Model                 | Accuracy |
|------------------------|----------|
| Logistic Regression    | 89.9%    |
| Decision Tree          | 99.4%    |
| K-Nearest Neighbors    | 91.9%    |
| Random Forest          | **99.88% ✅** |

✔️ **Random Forest outperformed all models** with the highest accuracy.  
✔️ Results were consistent across Python and Orange Data Mining workflows.  

## 🛠️ Tools & Libraries
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)  
- Orange Data Mining (workflow visualization)  

## 📎 Files
- `loan_approval.ipynb`: Main notebook with preprocessing, modeling, and evaluation  
- `workflow/`: Orange Data Mining workflow file (.ows)  
- `loan_approval_dataset.csv`: Dataset (optional or link in README)  

🔗Part of my [Elevvo](https://elevvo.tech/) Internship Projects

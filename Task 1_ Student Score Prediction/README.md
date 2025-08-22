# Task 1: Student Score Prediction

## 📌 Project Overview
This project predicts **students' exam scores** based on their study hours.  
It was completed as part of my **Elevvo Internship**.

## 📂 Dataset
- **Source**: [Student Performance Factors (Kaggle)](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors)  
- Features include study hours and related performance factors.  
- Target variable: **Final Exam Score**

## ⚙️ Steps
1. Data cleaning and basic visualization to understand the dataset  
2. Split data into training and testing sets  
3. Train regression models:
   - **Linear Regression**
   - **Polynomial Regression**
4. Evaluate and compare model performance  
5. Visualize predictions  

## 📊 Results
| Model                  | MAE   | R²   |
|-------------------------|-------|------|
| Linear Regression       | 0.92  | 0.88 |
| Polynomial Regression   | 0.27  | 0.99 |

✅ **Polynomial Regression outperformed Linear Regression** with a much lower MAE and higher R².  

## 🛠️ Tools & Libraries
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

## 📎 Files
- `student_score.ipynb`: Main notebook  
- `data/`: Dataset (optional or link in README)  

---
🔗 *Part of my [Elevvo](https://elevvo.tech/) Internship Projects*

# 📘 SemesterSense: MOOC Certificate Prediction

**Project Title:**  
Semester-Wise Student Engagement and Certification Prediction in MOOCs using Ensemble Learning

**Author:**  
Yarlagadda.Abhiram  
📧 yarlagaddaabhi5@gmail.com  
📞 9063313555

---

## 📌 Problem Statement

In Massive Open Online Courses (MOOCs), student engagement and certification rates vary significantly across semesters — Fall, Spring, and Summer. This project aims to:
- Analyze semester-wise engagement patterns.
- Predict the most likely semester for a student to earn a certificate.
- Apply ensemble learning techniques for robust classification and improved accuracy.

---

## 🗂️ Dataset Overview

The dataset includes:
- Engagement metrics (events, active days, etc.)
- Demographic and academic features
- Target: `semester` (Fall, Spring, or Summer)

📁 Dataset: The dataset used in this project is publicly available on Kaggle:
👉 [MOOC Dataset - Kaggle](https://www.kaggle.com/datasets/kanikanarang94/mooc-dataset)


---

## 🛠️ Technologies Used

- **Python**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – Machine Learning models & evaluation

---

## 🔍 Steps Involved

1. **Data Cleaning & Preprocessing**  
   - Missing value imputation  
   - Categorical encoding  
   - Feature scaling

2. **Exploratory Data Analysis (EDA)**  
   - Distribution plots (Bar, Box, Violin, KDE)  
   - Heatmap for feature correlation

3. **Modeling & Evaluation**  
   - Models: Logistic Regression, Decision Tree, Random Forest, KNN  
   - Metrics: Accuracy, Precision, Recall, F1-score  
   - Confusion matrices & classification reports

4. **Ensemble Learning**  
   - Bagging (with Decision Trees)  
   - AdaBoost  
   - Stacking (Logistic Regression, SVM, KNN)

---

## 🤖 Model Performance Comparison

This involves building and evaluating various machine learning models for classification. Below are the results of the models in terms of **Accuracy**, **Precision**, **Recall**, and **F1 Score**.

### 📊 Classification Models Comparison

| Model                | Accuracy  | Precision | Recall   | F1 Score |
|---------------------|-----------|-----------|----------|----------|
| Decision Tree        | 0.993469  | 0.983962  | 0.985333 | 0.984641 |
| Random Forest        | 0.946061  | 0.945933  | 0.858945 | 0.895882 |
| Logistic Regression  | 0.931710  | 0.899246  | 0.861772 | 0.879341 |
| KNN                  | 0.894165  | 0.844411  | 0.772377 | 0.801859 |

---

### 🔁 Ensemble Models Comparison

| Ensemble Model | Accuracy  | Precision | Recall   | F1 Score |
|----------------|-----------|-----------|----------|----------|
| Bagging        | 0.993416  | 0.982572  | 0.985570 | 0.984063 |
| Stacking       | 0.954151  | 0.921734  | 0.897582 | 0.909072 |
| AdaBoost       | 0.897579  | 0.869547  | 0.760071 | 0.803674 |

The Decision Tree and Bagging models achieved the highest performance across all metrics, showing strong generalization and consistency.



---

## 📈 Visualizations

- Semester-wise enrollment trend  
- Box & Violin plots for activity distribution  
- KDE plots for event density  
- Heatmaps for feature correlation  
- Confusion matrices for model evaluation  

---

## ✅ Conclusion

This project successfully demonstrates how ensemble learning can boost the prediction accuracy of semester-wise certificate outcomes in MOOCs. The insights derived can help educators design more engaging content for underperforming semesters.

---

## 🚀 Further Improvements

- Hyperparameter tuning with GridSearchCV
- Use of Deep Learning models (e.g., Neural Networks)
- Dashboard deployment using Streamlit or Flask



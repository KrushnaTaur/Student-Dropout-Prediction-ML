# 🎓 Student Dropout Prediction Using Machine Learning  
📂 Repository: **Student-Dropout-Prediction-ML**

This repository contains our **group-based Machine Learning mini-project**, where we developed a complete ML pipeline to predict *student dropout risk* using academic, demographic, and financial indicators.  
The goal of the project is to help educational institutions identify students who may require early support & intervention.

---

## 📁 Repository Content

| File | Description |
|---|---|
| **Student_Dropout_Prediction.ipynb** | Google Colab notebook with full pipeline (EDA → Preprocessing → PCA → Modeling → Evaluation) |
| **Student_Dropout_Prediction_Presentation.pdf** | Final presentation used for explanation & viva |
| **student_dropout.csv** | Dataset used for model training/testing |

---

## 🔍 Project Capabilities

✔ Exploratory Data Analysis  
> Age distribution | Gender vs Target | Course comparison | Financial indicators | Correlation Heatmap  

✔ Data Preprocessing  
> Encoding categorical features | Feature scaling | Train-test split | Outlier handling  

✔ PCA Dimensionality Reduction  
> Semester academic features reduced **12 → 2 components**  

✔ Machine Learning Models Trained  
- KNN  
- Naive Bayes  
- Decision Tree  
- Random Forest  
- Bagging  
- AdaBoost  
- Gradient Boosting  
- **Stacking Ensemble (Best Performer)**  

---

## 🏆 Final Model Performance

| Model | ROC-AUC |
|---|---|
| ⭐ **Stacking Ensemble** | **0.928** |

Best model selected due to:
- High generalization ability  
- Stable predictive performance  
- Superior AUC score among all models  

---

## 🛠 Tools & Technologies Used

| Category | Tools |
|---|---|
| Language | Python |
| Data Handling | Pandas, NumPy |
| Modeling | Scikit-Learn |
| Visualization | Matplotlib, Seaborn |
| Dimensionality Reduction | PCA |

---

## 📌 Conclusion

Our ML system successfully predicts at-risk dropout students with high accuracy.  
The model enables universities to take **proactive measures**, improve retention, and support student success.

---

> This was a **Group Mini Project** completed under academic requirements.

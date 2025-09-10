# 📊 Employee Data Science Analysis

A complete **data science project** analyzing employee data to uncover insights on **performance, retention, and attrition**.  
The project demonstrates **end-to-end machine learning workflow** including **EDA, preprocessing, model training, evaluation, and visualization**.

---

## 🚀 Project Overview

This project aims to answer key questions for HR and business decision-making:

- What factors influence employee **attrition** (whether they leave the company)?
- Which features are the most important in predicting employee retention?
- How do different models (Logistic Regression vs Random Forest) perform on this dataset?

The workflow includes:

1. **Data Loading & Cleaning**  
   - Handling missing values  
   - Encoding categorical features  
   - Scaling numeric variables  

2. **Exploratory Data Analysis (EDA)**  
   - Summary statistics  
   - Missing values check  
   - Histograms of numeric variables  
   - Correlation heatmap  

3. **Modeling**  
   - Logistic Regression  
   - Random Forest Classifier  

4. **Evaluation**  
   - Accuracy, Precision, Recall, F1-score, ROC-AUC  
   - Confusion matrices  
   - Feature importance visualization  

5. **Reporting**  
   - Interactive Jupyter Notebook  
   - Executed notebook with results  
   - Exported HTML and PDF reports  

---


## 📊 Results
 Model Performance (example results)
 Model	Accuracy	Precision	Recall	F1-score	ROC-AUC
 Logistic Regression	0.60	0.42	0.50	0.43	0.59
 Random Forest	0.75	0.56	0.60	0.55	0.72

➡️ Random Forest outperformed Logistic Regression in almost all metrics, making it a better choice for this dataset.

## 📈 Visuals

The notebook includes:

- Histograms for each numeric feature
  (e.g., Age, Salary, YearsAtCompany)

- Correlation Heatmap
  To identify relationships between numeric variables

- Confusion Matrices
  To visualize classification performance

- Feature Importances (Random Forest)

  Highlights top drivers of attrition/performance

## 🛠️ Technologies Used

- Python 3.x

- Jupyter Notebook

- Pandas & NumPy → Data handling

- Matplotlib → Visualizations

- Scikit-learn → Preprocessing, modeling, evaluation


## 🔮 Next Steps / Future Work

- Perform hyperparameter tuning (GridSearchCV)

- Apply k-fold cross-validation for robust performance estimates

- Use SHAP or LIME for explainability of model predictions

- Build an interactive dashboard (Streamlit or Flask) for HR decision-makers

- Deploy as a simple web app for live employee retention predictions

## 👨‍💻 Author

Your Name - Harsh Tripathi

Engineering Student @ IIIT Raichur
📧 tripathiharsh2104@gmail.com

🔗 LinkedIn

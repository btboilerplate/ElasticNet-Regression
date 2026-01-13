# 📈 ElasticNet Regression on Housing Dataset

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-ElasticNet%20Regression-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 🔹 Project Overview
This project implements **ElasticNet Regression** using scikit-learn to predict house prices from a housing dataset.
ElasticNet combines **L1 (Lasso)** and **L2 (Ridge)** regularization, balancing feature selection and coefficient
stability, making it effective when features are correlated.

The notebook demonstrates the complete machine learning workflow, including data loading, preprocessing,
model training, evaluation, and residual analysis.

---

## 📂 Repository Contents
ElasticNet_Regression  
│  
├── ElasticNet_Regression.ipynb  
├── housing.csv  
├── residual_distribution.png  
└── README.md  

---

## 📊 Dataset
- **File:** housing.csv  
- **Type:** Tabular housing data  
- **Purpose:** Used to train and evaluate an ElasticNet Regression model for house price prediction  

---

## 🛠️ Libraries & Tools Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- scikit-learn  

---

## ⚙️ Project Workflow
1. Load the housing dataset  
2. Perform train-test split  
3. Train an ElasticNet Regression model  
4. Predict house prices on test data  
5. Evaluate model performance using R² Score  
6. Analyze residual distribution  

---

## 📈 Model Evaluation

**R² Score:** 0.6398401841321038  

**Interpretation:**  
The model explains approximately **64% of the variance** in housing prices.
By combining L1 and L2 regularization, ElasticNet maintains strong predictive
performance while improving model robustness and handling correlated features.

---

## 📉 Residual Analysis

**Residual Distribution (y_test − ridge_pred):**

![Residual Distribution](residual_distribution.png)

### Key Insights
- Residuals are approximately normally distributed  
- Indicates that regression assumptions are largely satisfied  
- ElasticNet provides a balance between sparsity and stability  

---

## 📌 Key Observations
- ElasticNet combines the strengths of Ridge and Lasso regression  
- Helps manage multicollinearity among features  
- Provides stable performance with controlled model complexity  

---

## ▶️ How to Run the Project
1. Clone the repository  
```
git clone https://github.com/your-username/ElasticNet_Regression.git  
```
2. Install required libraries  
```
pip install numpy pandas matplotlib scikit-learn  
```
3. Open `ElasticNet_Regression.ipynb`  
4. Run all cells sequentially  

---

## 🚀 Future Enhancements
- Tune alpha and l1_ratio using cross-validation  
- Compare ElasticNet with Ridge and Lasso results  
- Add RMSE and MAE evaluation metrics  

---

# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict the **selling price of used Indian cars** based on historical data.  
The solution follows a complete **end-to-end machine learning lifecycle**, including data preprocessing, exploratory data analysis, model comparison, and final model selection.

The dataset is sourced from **CarDekho**, representing real-world Indian used car listings.

---

## 📊 Dataset
- **Source:** CarDekho (Kaggle)
- **Type:** Indian used car data
- **Target Variable:** `selling_price`
- **Key Features:**
  - Year
  - Kilometers Driven
  - Fuel Type
  - Seller Type
  - Transmission
  - Ownership

> Note: The dataset contains real-world noise such as negotiation effects and missing condition details, making the prediction task realistic.

---

## ⚙️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- VS Code (Jupyter Notebook)

---

## 🔄 Machine Learning Workflow
1. Data Loading and Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature Encoding  
4. Train-Test Split  
5. Model Training and Comparison  
6. Model Evaluation  
7. Final Model Selection  

---

## 🤖 Models Trained
Three regression models were trained and evaluated:

| Model | Purpose |
|-----|------|
| Linear Regression | Baseline model |
| Random Forest Regressor | Capture non-linear relationships |
| XGBoost Regressor | Final optimized model |

---

## 📈 Model Evaluation Metrics
The models were evaluated using:
- **R² Score**
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**

### Results Summary

| Model | R² | MAE (₹) | RMSE (₹) |
|-----|----|--------|---------|
| Linear Regression | 0.48 | 2.41 L | 4.51 L |
| Random Forest | 0.77 | 1.57 L | 3.03 L |
| **XGBoost** | **0.77** | **1.60 L** | **2.98 L** |

---

## 🏆 Final Model Selection
XGBoost was selected as the final model due to:
- Best overall R² score
- Better generalization on unseen data
- Strong handling of non-linear relationships

---

## 🔍 Key Insights
- Newer cars tend to have higher selling prices
- Diesel and automatic cars are generally priced higher
- Higher kilometers driven negatively impact price
- Tree-based models outperform linear models for this problem

---

## ⚠️ Limitations
- Car condition and accident history are not available
- Location-based pricing variations are not included
- Negotiation effects are not captured

---

## 🚀 Future Improvements
- Hyperparameter tuning
- Cross-validation
- Feature engineering (log transformation, outlier handling)
- Model deployment using Streamlit

---

## 📌 Conclusion
This project demonstrates a **realistic and production-style ML workflow**, emphasizing proper model comparison, evaluation, and selection rather than chasing inflated metrics.


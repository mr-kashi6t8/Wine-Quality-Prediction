# 🍷 Wine Quality Prediction (Red Wine)

## 📌 Overview  
This project predicts **red wine quality** using **XGBoost Classifier**.  
We perform **EDA**, **feature engineering**, **SMOTE for imbalance handling**, and **pipeline automation** to classify wines as *good* or *bad*.  

---

## 📂 Dataset  
- **Source**: UCI ML Wine Quality Dataset (`winequality-red.csv`)  
- **Target Variable**: Wine quality (`good` vs `bad`)  

---

## 🔍 Exploratory Data Analysis (EDA)  
- Summary statistics & correlation analysis  
- Feature distributions across wine quality  
- Boxplots, barplots & heatmaps for insights  

---

## ⚙️ Feature Engineering  
- Dropped low-impact features: `pH`, `density`, `chlorides`, etc.  
- Added interaction features:  
  - `acid_sugar_ratio`  
  - `sulphates_alcohol_ratio`  
  - `acid_alcohol_interaction`  
  - Polynomial features (`alcohol_sq`, `residual_sugar_sq`, `log residual_sugar`)  

---

## 🤖 Model & Pipeline  
- **Preprocessing**: StandardScaler  
- **SMOTE**: Synthetic Minority Oversampling to balance classes  
- **Model**: `XGBClassifier` with tuned hyperparameters  

---

## 📈 Results  
- **Accuracy**: ~0.87  
- **ROC AUC (5-fold CV)**: ~0.92  
- **Classification Report**: Balanced precision/recall across classes  
- **Confusion Matrix**: Clear separation between good vs bad wines  
- **Feature Importance**: Alcohol & sulphates were top predictors  

---

## 🖼️ Visualizations  
- Feature Importances (XGBoost)  
- Actual vs Predicted Probabilities  
- Correlation heatmap & quality-based plots  

---

## 🚀 Tech Stack  
- **Python** 🐍  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`, `imblearn`, `skimpy`  

---

## 📌 Key Learning  
- How feature engineering improves model performance  
- Importance of handling **imbalanced data** with SMOTE  
- Interpreting **feature importance** in XGBoost  

---

## 📜 License  
This project is for educational purposes. Feel free to use and modify it.  


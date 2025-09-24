# 🏥 Health Insurance Premium Prediction  

## 📌 Project Overview  
This project predicts **health insurance premiums** based on customer demographics and lifestyle factors using Machine Learning models. The goal is to assist insurers and healthcare providers in **understanding premium drivers** and providing **fair, data-driven premium estimates**.  

## ✨ Key Features  
- Built regression-based ML models to **predict insurance premiums** with high accuracy.  
- Conducted **Exploratory Data Analysis (EDA)** to identify important features influencing premiums (age, BMI, smoking habits, region, etc.).  
- Implemented **feature engineering and preprocessing** (encoding categorical variables, normalization, and handling skewed distributions).  
- Compared multiple ML algorithms:  
  - Linear Regression  
  - Random Forest Regressor  
  - XGBoost Regressor  
- Achieved improved accuracy through **hyperparameter tuning** and cross-validation.  
- Visualized insights using **Matplotlib & Seaborn**.  

## 🛠️ Tech Stack  
- **Programming Language:** Python  
- **Libraries:** pandas, NumPy, scikit-learn, XGBoost, Matplotlib, Seaborn, Jupyter Notebook  

## 📊 Workflow  
1. **Data Collection & Cleaning**  
   - Loaded dataset and handled missing values/outliers.  
2. **Exploratory Data Analysis (EDA)**  
   - Visualized feature distributions and correlations.  
   - Identified significant factors affecting insurance cost.  
3. **Feature Engineering**  
   - One-hot encoding for categorical variables.  
   - Normalization of continuous variables.  
4. **Model Building**  
   - Trained and evaluated multiple regression models.  
   - Used GridSearchCV for hyperparameter tuning.  
5. **Model Evaluation**  
   - Compared models using R², RMSE, and MAE metrics.  

## 🚀 Results  
- Best-performing model: **XGBoost Regressor**  
- Achieved **high prediction accuracy** with significant improvement over baseline Linear Regression.  
- Key insights: **smoking, BMI, and age** are major factors influencing premium costs.  

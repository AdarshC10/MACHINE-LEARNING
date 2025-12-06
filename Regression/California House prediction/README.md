# 🏠 California Housing Price Prediction using Machine Learning

## 📌 Project Overview
This project predicts the median house prices in California using machine learning regression models. The dataset is sourced from the 1990 U.S. Census and provided by Scikit-learn.

The goal is to analyze the influence of income, population, house age, and location on house prices and build accurate prediction models.

---

## 📂 Dataset Information
- Source: Scikit-learn California Housing Dataset  
- Total Rows: 20,640  
- Features: 8 Numerical Features  
- Target Variable: Median House Value  

| Feature | Description |
|--------|-------------|
| MedInc | Median Income |
| HouseAge | Median House Age |
| AveRooms | Average Rooms |
| AveBedrms | Average Bedrooms |
| Population | Population |
| AveOccup | Average Occupancy |
| Latitude | Latitude |
| Longitude | Longitude |

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 🔄 Workflow
1. Data Loading  
2. Data Cleaning and Validation  
3. Exploratory Data Analysis (EDA)  
4. Train-Test Split  
5. Feature Scaling  
6. Model Training  
7. Model Evaluation  
8. Result Comparison  
9. Visualization  

---

## 🤖 Machine Learning Models
- Linear Regression  
- Random Forest Regressor  

---

## 📊 Model Evaluation Results

| Model | RMSE | R² Score |
|--------|--------|----------|
| Linear Regression | 0.745 | 0.575 |
| Random Forest | 0.505 | 0.805 ✅ |

✅ Random Forest gives the best prediction accuracy.

---

## 📈 Visualizations
- Box Plot for Outliers  
- Residual Plot for Linear Regression  
- Feature Importance Plot for Random Forest  

---

## 🏆 Conclusion
- Median income and location are the strongest predictors.
- Random Forest significantly outperforms Linear Regression.
- The model is reliable for predicting house values.

---

## 🚀 Future Enhancements
- Hyperparameter tuning
- Web App deployment (Flask/Streamlit)
- Real-time data integration
- Deep learning models

---



# 🏠 Boston House Price Prediction using Machine Learning

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/ed2a30cf-a32f-433a-adba-bf89b15b8fd7" />

This project focuses on predicting house prices using the **Boston
Housing Dataset** with **Simple Linear Regression** and **Multiple
Linear Regression** models.

------------------------------------------------------------------------

## 📌 Project Overview

The objective of this project is to: - Explore and understand real-world
housing data - Perform data preprocessing - Apply **Linear
Regression** - Evaluate model performance using statistical error
metrics

------------------------------------------------------------------------

## 🧰 Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Scikit-learn

------------------------------------------------------------------------

## 📂 Dataset Information

-   **Total Rows:** 506
-   **Total Columns:** 14
-   **Target Variable:** `Price` (Median value of homes in \$1000s)

### Features Description:

-   `CRIM` -- Crime rate
-   `ZN` -- Residential land proportion
-   `INDUS` -- Industrial land proportion
-   `CHAS` -- Near Charles River
-   `NOX` -- Air pollution
-   `RM` -- Average rooms per house
-   `AGE` -- Old house ratio
-   `DIS` -- Distance to job centers
-   `RAD` -- Highway access
-   `TAX` -- Property tax
-   `PTRATIO` -- Teacher-student ratio
-   `B` -- Population diversity metric
-   `LSTAT` -- Lower status population %

------------------------------------------------------------------------

## 🔧 Data Preprocessing

-   Removed unnecessary column `Unnamed: 0`
-   No missing values found
-   Data cleaning not required

------------------------------------------------------------------------

## 📊 Simple Linear Regression

-   **Independent Variable:** `LSTAT`
-   **Target Variable:** `Price`

### Evaluation Metrics:

-   **MAE:** 4.18
-   **MSE:** 33.51
-   **RMSE:** 2.40
-   **R² Score:** 0.54

------------------------------------------------------------------------

## 🤖 Multiple Linear Regression

Used all features to predict price.

### Evaluation Metrics:

-   **MAE:** 3.18\
-   **MSE:** 24.29\
-   **RMSE:** 4.92\
-   **R² Score:** 0.66

------------------------------------------------------------------------

## ▶️ How to Run the Project

``` bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run the Python file or Jupyter Notebook after placing `boston.csv` in
the project directory.

------------------------------------------------------------------------

## ✅ Conclusion

-   Multiple Linear Regression performed better than Simple Linear
    Regression.
-   House prices are strongly influenced by multiple factors.
-   The project demonstrates effective regression modeling and
    evaluation.

------------------------------------------------------------------------

## 🧑‍💻 Author

**Adarsh**\
Machine Learning & Data Analytics Enthusiast

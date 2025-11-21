# 🏠 Saudi Arabia Real Estate Price Prediction

## 📌 Project Overview
A Machine Learning project aimed at predicting residential real estate prices in Saudi Arabia (Riyadh, Jeddah, Dammam, etc.) based on property features. This project utilizes **Random Forest Regression** to analyze factors influencing market value.

## 🎯 Key Features & Methodology
* **Data Collection:** Utilized real-world dataset from "Aqar" application (3,700+ listings).
* **Data Cleaning:** Performed statistical cleaning to remove outliers (e.g., unrealistic prices/sizes) ensuring high data quality.
* **Feature Engineering:** - Handled high cardinality for districts (Top 50 districts focus).
    - One-Hot Encoding for categorical variables (City, Front).
* **Modeling:** Built and trained a **Random Forest Regressor**.

## 📊 Results
The model achieved the following performance metrics on unseen test data:
* **Accuracy (R2 Score):** 42.1% (Baseline model with location engineering).
* **Mean Absolute Error (MAE):** ±13,752 SAR.

## 🛠 Tools Used
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib.
* **Deployment:** Model saved as `.pkl` for future integration.

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies: `pip install pandas scikit-learn seaborn`.
3. Run the Jupyter Notebook `Saudi_Real_Estate_Price_Prediction.ipynb`.

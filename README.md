# 🏠 House Price Prediction

## 📌 Project Overview

This project was completed as part of my internship Week 1 assignment. The goal was to build a machine learning model capable of predicting house prices based on various property features such as area, number of bedrooms, bathrooms, parking availability, furnishing status, and other amenities.

The project includes data cleaning, exploratory data analysis (EDA), visualization, model training, evaluation, and business insights.

---

## 🎯 Objectives

* Analyze housing market data.
* Identify factors affecting house prices.
* Build and evaluate regression models.
* Compare model performance.
* Generate actionable insights for real estate businesses.

---

## 📂 Dataset

Dataset Source:

**Housing Prices Dataset (Kaggle)**

Features include:

* Area
* Bedrooms
* Bathrooms
* Stories
* Parking
* Main Road Access
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Preferred Area
* Furnishing Status

Target Variable:

* **Price**

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 📊 Data Preprocessing

The following preprocessing steps were performed:

* Loaded and explored the dataset
* Checked for missing values
* Removed duplicate records
* Encoded categorical variables using One-Hot Encoding
* Prepared data for machine learning models

---

## 🤖 Machine Learning Models

### 1. Linear Regression

Used as the baseline regression model.

### 2. Random Forest Regressor

Used to compare performance against Linear Regression.

---

## 📈 Model Performance

| Model                   | MAE       | RMSE      | R² Score |
| ----------------------- | --------- | --------- | -------- |
| Linear Regression       | 970,043   | 1,324,507 | 0.653    |
| Random Forest Regressor | 1,013,969 | 1,398,116 | 0.613    |

### Best Performing Model

✅ Linear Regression

---

## 📉 Visualizations

The project includes:

### House Price Distribution

* Histogram showing the distribution of housing prices.

### Correlation Heatmap

* Relationship between house prices and other features.

### Actual vs Predicted Prices

* Comparison of model predictions with actual values.

---

## 🔍 Key Insights

* Property area has the strongest impact on house prices.
* Bathrooms, parking spaces, and number of stories positively influence property value.
* Air conditioning and preferred area significantly increase housing prices.
* Furnishing status affects the final market value of a property.
* Most houses fall within the mid-price range, while a small number of properties are significantly more expensive.

---

## 💡 Business Recommendation

Real estate businesses should focus on promoting larger properties with modern amenities such as air conditioning, parking facilities, and multiple bathrooms. Properties located in preferred areas tend to achieve higher market prices and attract greater buyer interest.

---

## 📁 Project Structure

```text
HousePricePrediction/

├── analysis.ipynb
├── Housing.csv
├── summary.pdf
├── charts/
│   ├── price_distribution.png
│   ├── correlation_heatmap.png
│   └── actual_vs_predicted.png
├── requirements.txt
└── README.md
```

---

## 🚀 Future Improvements

* Hyperparameter tuning
* Feature engineering
* XGBoost Regressor
* Cross-validation
* Deployment using Streamlit

---

## 👨‍💻 Author

**Parit Gupta**

Data Science Intern – Week 1 Project

# house-price-week5
Week 5 Assignment - House Price Prediction (Data Preprocessing &amp; Feature Engineering)
# 🏡 House Price Prediction - ML Pipeline Project

## 🎯 Overview
This repository contains work on a machine learning pipeline to predict house prices using the Ames Housing dataset.  
Currently, it includes data preprocessing and feature engineering as part of an internship assignment (Week 5).

---

## 📂 Project Structure

```
house-price-prediction/
│
├── data/            # Input CSVs from Kaggle
│   ├── train.csv
│   └── test.csv
│
├── notebooks/       # Jupyter notebooks by phase
│   └── week5_preprocessing.ipynb
│
├── outputs/         # (Optional) Future plots or model files
├── README.md
└── requirements.txt # For dependencies (planned)
```

---

## ✅ Included (Week 5)
- Handled missing values
- Created new features like `TotalSF`, `TotalBath`, `AgeAtSale`
- Label encoded categorical variables
- Visualized `SalePrice` using log transformation
- Added a basic outlier flag

---

## 🔭 Possible Future Scope
This repo is structured to allow for future additions such as:
- Model training and evaluation (e.g., Ridge, XGBoost)
- Hyperparameter tuning
- Feature selection techniques
- Saving models or deploying via an API

These steps may be added as part of future assignments or personal experimentation.

---

## 📌 Usage
Run `notebooks/week5_preprocessing.ipynb` to view all data processing steps.  
Dataset files should be placed in the `data/` folder.

---

## 📚 Dataset
- [Kaggle: House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

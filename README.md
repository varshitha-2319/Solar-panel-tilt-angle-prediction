# 🌞 Machine Learning-Based Optimization of Solar Panel Tilt Angles Using CatBoost


---

## 🚀 Abstract
This project presents a machine learning-based approach to optimize the **tilt angle** of solar panels dynamically using the **CatBoost Regressor**, trained on NASA POWER data.  
The goal is to enhance solar energy efficiency by predicting the best tilt based on solar geometry and meteorological conditions.

---

## ⚙️ Methodology
- Dataset: NASA POWER (2021–2024)
- Features: GHI, DNI, DHI, Temperature, Wind Speed, Humidity, Solar Zenith Angle
- Model: **CatBoost Regressor**
- Techniques:
  - Data Cleaning (IQR, Min-Max)
  - Feature Engineering (SZA, Lag features)
  - Hyperparameter Tuning (Grid + Bayesian Optimization)
  - Evaluation (RMSE, MAE, R²)

---

## 📊 Results
| Model | RMSE | MAE | R² Score | Accuracy |
|--------|------|-----|-----------|-----------|
| **CatBoost** | **2.45** | **1.76** | **0.92** | **99.62%** |
| XGBoost | 2.89 | 2.10 | 0.88 | 89.8% |
| LightGBM | 2.78 | 1.98 | 0.89 | 88.4% |
| Random Forest | 3.02 | 2.22 | 0.86 | 87.6% |

---



#  Bike Rental Demand Prediction

This project uses a **Linear Regression** model to predict daily **bike rental counts** based on environmental conditions such as **temperature**, **humidity**, and **windspeed**.

---

## 📌 Project Overview

Bike-sharing services rely on accurate demand forecasting to optimize fleet distribution and improve user experience. This project aims to help predict rental demand using basic weather features, providing a foundation for smarter resource planning.

---

## 🧠 Objectives

- Build a **Linear Regression** model to predict rental counts.
- **Preprocess** and clean the dataset for modeling.
- **Split** the data into training and testing sets.
- Evaluate model performance using the **R² score**.
- Analyze the **impact of features** on predictions.
- Improve model accuracy through **feature tuning and optimization**.

---

## 🔢 Features Used

| Feature     | Description                              |
|-------------|------------------------------------------|
| `temperature` | Normalized temperature (in Celsius)     |
| `humidity`    | Relative humidity percentage             |
| `windspeed`   | Wind speed (normalized)                 |

> 🏁 Target Variable: `rental_count` – the number of bikes rented on a given day.

---

## 🛠️ Tech Stack

- Python
- pandas, numpy
- scikit-learn (LinearRegression, train_test_split, metrics)
- matplotlib, seaborn (for EDA and visualizations)

---

## 📈 Model Workflow

1. **Load & Inspect** data
2. **Clean** missing or irrelevant values
3. **Visualize** feature distributions and correlations
4. **Split** data into training and testing sets (e.g., 80/20)
5. **Train** a Linear Regression model
6. **Evaluate** using R² score
7. **Tune** features and compare results

---

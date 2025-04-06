# 🚕 Uber Fare Prediction 🧠📊

Welcome to the **Uber Fare Prediction Case Study**! In this project, we dive into the world of data science and machine learning to predict the fare of Uber rides in New York City 🗽, based on various features such as pickup and drop-off locations, date & time, and passenger count.

---

## 🧠 Objective

To build a robust regression model that accurately predicts Uber fares based on ride features using advanced machine learning algorithms and thoughtful feature engineering.

---

## 🛠️ Tech Stack

- 📌 **Python**
- 🧮 **Pandas, NumPy** – Data manipulation
- 📊 **Matplotlib, Seaborn, Plotly, Folium** – Data visualization
- 🔍 **Scikit-Learn** – Linear & polynomial regression
- ⚡ **XGBoost & LightGBM** – Advanced ensemble modeling
- 📏 **StandardScaler** – Feature scaling

---

## 🧹 Data Preprocessing

- ✅ Removed unnamed index column
- 🚫 Filtered invalid fares (negative/zero values)
- ❌ Dropped missing coordinates
- 🗺️ Applied geographical bounding box for NYC

---

## 🔧 Feature Engineering

- 🧭 Distance between pickup and drop-off points (Haversine formula)
- ⏰ Extracted hour, day, month, weekday from datetime
- 👥 One-hot encoding for rush hours vs. non-rush hours

---

## 📊 Exploratory Data Analysis

### 📈 Fare Amount Distribution
> Visualizing fare trends and spotting outliers.

### 📍 Pickup Location Heatmap
> Using `Folium` to highlight ride hotspots across NYC.

### ⏱️ Rush Hour Impact
> Analyzed fare trends during peak hours.

### 🔗 Correlation Matrix
> Explored relationships between features.

---

## 🤖 Models Implemented

| Model                   | Description                               |
|------------------------|-------------------------------------------|
| 📈 Linear Regression    | Simple baseline model                     |
| 🔢 Polynomial Regression| Captures non-linearity in fare prediction|
| ⚙️ XGBoost              | Gradient boosting with regularization     |
| 🌟 LightGBM            | Fast & efficient tree-based boosting      |
| 🧠 Ensemble Model      | Weighted average of XGB & LGBM outputs    |

---

## 🧪 Model Evaluation

- 📊 Evaluation Metrics: **RMSE**, **R² Score**
- 🏆 **Ensemble model** outperformed all individual models.
- 📈 Feature importance analysis for transparency

---

## ✅ Results

🚀 **Key Insights:**
- Distance is the most influential feature 🗺️
- Fare prices tend to rise during rush hours ⏱️
- Ensemble methods deliver significantly better accuracy than individual models 🎯

---

## 📌 Conclusion

This case study demonstrates the power of combining:
- ✅ Solid data cleaning
- ✅ Feature-rich engineering
- ✅ Exploratory visualization
- ✅ Advanced ML modeling

...to achieve **accurate fare prediction** in a real-world dataset.

---

## 🤝 Let's Connect!

If you like this Case-Study Report, feel free to ⭐️ the repo or connect with me on [LinkedIn](https://www.linkedin.com/in/savinay-pandey/) 💼

---

> ✨ “Data is the new oil, but it's crude until refined by analysis.” – Aparichit


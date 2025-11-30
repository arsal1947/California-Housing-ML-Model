# California Housing Price Prediction

## 🏡 Project Overview
This project predicts the **median house values** in California using the **California Housing Dataset**.  
It demonstrates the complete machine learning workflow: data exploration, preprocessing, feature engineering, model training, evaluation, and visualization.

---

## 🎯 Objective
- Build a machine learning model to accurately predict housing prices in California.  
- Explore the impact of features such as median income, house age, and location on the housing prices.  
- Compare different regression models and evaluate their performance.

---

## 📊 Dataset
- **Source:** [California Housing Dataset from Kaggle](https://www.kaggle.com/datasets/dhirajnirne/california-housing-data)  
- **Features:**
  | Feature | Description |
  |---------|-------------|
  | MedInc  | Median income in block |
  | HouseAge | Median house age in block |
  | AveRooms | Average rooms per household |
  | AveBedrms | Average bedrooms per household |
  | Population | Population in block |
  | AveOccup | Average occupancy per household |
  | Latitude | Block latitude |
  | Longitude | Block longitude |
- **Target:** `MedHouseVal` – Median house value in USD (scaled)

---

## 🔧 Workflow
1. **Data Loading:** Load dataset using `scikit-learn`.  
2. **Exploratory Data Analysis (EDA):** Visualize distributions, correlations, and missing values.  
3. **Data Preprocessing:** Handle missing values, encode features if necessary, scale/normalize numeric features.  
4. **Feature Engineering:** Create new features if beneficial.  
5. **Model Training:** Train regression models (e.g., Linear Regression, Random Forest Regressor).  
6. **Evaluation:** Use metrics like `RMSE`, `MAE`, `R²` to measure model performance.  
7. **Prediction:** Make predictions on test data and visualize results.

---

## 🧰 Technologies & Libraries
- Python 3.x  
- Jupyter Notebook  
- Libraries: `numpy`, `pandas`, `matplotlib`,  `scikit-learn`, `joblib` (for saving models)

---

## 🚀 How to Run
1. Clone this repository.

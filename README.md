# 📊 Customer Churn Prediction Project

This project focuses on predicting telecom customer churn using Machine Learning, Deep Learning, and interactive Data Visualization. The goal is to help businesses identify customers at risk of leaving and understand the main churn drivers.

---

## 🧹 1. Data Preprocessing

- Loaded and cleaned telecom churn dataset.
- Filled missing values in `TotalCharges`.
- Converted categorical columns using:
  - Label Encoding  
  - One-Hot Encoding  
- Scaled numerical features for ML & Deep Learning.
- Split data into **train/test** sets.

---

## 📊 2. Exploratory Data Analysis (EDA)

Using **Plotly** interactive visualizations:

- Heatmap correlation between variables.
- Churn distribution plot.
- Impact of tenure.
- Payment method analysis.
- Internet service & contract type insights.

These visualizations helped identify key churn factors.

---

## 🤖 3. Machine Learning Models

Trained multiple algorithms:

- Random Forest
- Logistic Regression
- XGBoost
- KNN
- SVM

### 🧪 Model Evaluation
Metrics used:
- R² Score  
- RMSE  
- Accuracy (for classification version)

---

## 🔗 4. Stacking Ensemble

Created a powerful stacking model combining:

- **Random Forest**
- **Linear Regression**
- **XGBoost**

Achieved excellent results:

- **R²: 0.998**
- **RMSE: ~99.4**

---

## 🧠 5. Deep Learning Model

Built a neural network using **TensorFlow/Keras**:

- Dense layers
- Dropout regularization
- EarlyStopping
- Adam Optimizer

The DL model achieved competitive predictive performance and stability.

---

## 📈 6. Final Results

- High model performance across multiple techniques.
- Strong generalized predictions.
- Complete insights into churn patterns.
- Visualization dashboard for decision-makers.

---

## 🛠 Tech Stack

| Category | Tools |
|---------|-------|
| Language | Python |
| Data | Pandas, NumPy |
| ML | Scikit-Learn |
| DL | TensorFlow / Keras |
| Visualization | Plotly, Matplotlib, Seaborn |
| IDE | VS Code / Jupyter Notebook |

---

## 📂 Project Structure


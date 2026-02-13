# 🏠 House Price Prediction (Linear Regression)

This project predicts house prices using a **Linear Regression model** trained on the **California Housing dataset**.

It demonstrates a complete Machine Learning workflow:
- Dataset loading
- Data cleaning (missing values handling)
- Feature selection
- Train-test split
- Model training
- Evaluation (MSE, RMSE, R²)
- Predictions generation

---

## 📂 Dataset

- **Name:** California Housing Dataset  
- **Source:** `sklearn.datasets.fetch_california_housing`
- **Rows:** 20,640  
- **Features:** 8  
- **Target:** `MedHouseVal` (Median House Value)

---

## ⚙️ Features Used

The model uses the following 8 features:

- MedInc (Median Income)
- HouseAge (House Age)
- AveRooms (Average Rooms)
- AveBedrms (Average Bedrooms)
- Population
- AveOccup (Average Occupancy)
- Latitude
- Longitude

---

## 🧹 Data Cleaning

- Checked for missing values using:
  ```python
  df.isnull().sum()
  ```
- If missing values existed, they were filled using the column median.

---

## 🧠 Model Used

- Algorithm: Linear Regression
- Library: scikit-learn
- Train/Test Split: 80% train, 20% test

---

## 📊 Evaluation Metrics

The model was evaluted using:
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score

---

## ✅ Results

The Linear Regression model was evaluated on the test set using standard regression metrics:
- MSE (Mean Squared Error): 0.5559
- RMSE (Root Mean Squared Error): 0.7456
- R² Score: 0.5758

---

## 🔮 Sample Predictions

Sample predictions are saved in:
📁`results/sample_predictions.csv`

---

## 🚀 How to Run

**1)Install dependencies**
```bash
pip install -r requirements.txt
```

**2)Run the notebook**
```bash
jupyter notebook
```

---

## 📌 Project Deliverables
**✅ Notebook**(`notebook.ipynb`)
**✅ README**(`README.md`)
**✅ Results section**(`metrics`)
**✅ Sample predictions file**(`results/sample_predictions.csv`)

---

## 📎 Author
Created by: **Your Name**
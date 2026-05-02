# ☕ Café Sales Analytics & Forecasting

## 📌 Overview

This project analyzes café transactional data and builds a **time-series forecasting model** to predict future sales.
The workflow covers data cleaning, exploratory analysis, feature engineering, and machine learning.

---

## 🎯 Problem Statement

Raw transactional data often contains inconsistencies and missing values, making it difficult to extract reliable business insights.

This project aims to:

* Clean and validate sales data
* Identify trends in customer behavior and revenue
* Build a forecasting model for short-term sales prediction

---

## 🧠 Approach

### 1. Data Cleaning

* Handled missing values in `Total Spent` by reconstructing using:

  * `Quantity × Price Per Unit`
* Converted columns to correct data types
* Validated transactional consistency

---

### 2. Exploratory Data Analysis (EDA)

* Daily, weekly, and monthly sales trends
* Payment method analysis
* Location-based revenue distribution

---

### 3. Feature Engineering

To improve model performance, additional features were created:

* `Day` → Time index
* `Lag1` → Previous day sales
* `RollingMean7` → 7-day moving average

---

### 4. Modeling

#### Baseline Model

* Linear Regression using only time index (`Day`)
* Captured overall trend but failed to model fluctuations

#### Improved Model

* Added `Lag1` and `RollingMean7`
* Better captured short-term variations in sales

---

### 5. Evaluation

* Metric used: **Mean Absolute Error (MAE)**
* Improved model showed better alignment with actual sales trends compared to baseline

---

## 📈 Results & Insights

* Sales show significant daily fluctuations
* Simple time-based models are insufficient for capturing real-world behavior
* Feature engineering significantly improves prediction quality
* Forecasting provides a rough estimate of short-term sales trends

---

## ⚠️ Limitations

* Dataset contains only 1 year of data
* Limited ability to capture long-term seasonality
* External factors (holidays, promotions) not included
* Forecasting is suitable only for short-term predictions

---

## 🚀 Future Improvements

* Incorporate advanced models (ARIMA, Prophet)
* Add external features (holiday, demand patterns)
* Improve forecasting with dynamic lag updates

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib
* Scikit-learn

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

---

## 📂 Project Structure

```
cafe-sales-analysis/
│
├── data/
├── notebooks/
├── src/
├── README.md
```

---

## 💡 Key Takeaway

This project highlights how **data cleaning and feature engineering directly impact model performance**, even when using simple machine learning algorithms.

---

## 👤 Author

**Jasmin Banu M**

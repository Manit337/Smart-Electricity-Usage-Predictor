# ⚡ Smart Electricity Usage Predictor

**Project Title:** Smart Electricity Usage Predictor  
**Author:** Manit Gupta  
**Domain:** AI in Daily Life (Regression + Time-Series Forecasting)  
**IEEE Technical Team Individual Project — Semester 2**

---

## 📌 Project Overview

The **Smart Electricity Usage Predictor** is a Machine Learning-based system that predicts the **next-day household electricity consumption** using historical daily electricity usage data.

This project demonstrates how AI can help optimize energy usage, detect high consumption patterns, and support smart home energy management.

---

## 🎯 Objective

To build an end-to-end regression model that:

- Takes past electricity usage as input  
- Predicts tomorrow’s electricity consumption  
- Visualizes actual vs predicted usage  
- Generates a peak usage alert if consumption is high  

---

## 🚀 Features

✅ Load daily electricity usage dataset (CSV)  
✅ Preprocess and normalize time-series data  
✅ Create lag-based features (previous days usage)  
✅ Train a regression model (Random Forest Regressor)  
✅ Predict next-day electricity consumption  
✅ Plot Actual vs Predicted graph  
✅ Optional Peak Usage Alert system  

---

## 🧠 Machine Learning Approach

This project uses a **supervised regression model**:

- **Input Features:**  
  - Yesterday’s usage  
  - Usage from 2 days ago  
  - Usage from 3 days ago  

- **Target Output:**  
  - Today’s electricity usage (kWh)

### Model Used:
- **Random Forest Regression**

---

## 📂 Dataset Format

The input dataset must be a CSV file named:


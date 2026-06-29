# Crop-Recommendation
# 🌾 Crop Recommendation System Using Machine Learning

## 📌 Project Overview

This project applies **Machine Learning** to solve a real-world agricultural problem by recommending the most suitable crop based on soil nutrients and environmental conditions. Using features such as Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, and Rainfall, the system helps farmers make data-driven decisions to improve crop productivity.

> **🏆 Best Model:** Random Forest with **99.32% Testing Accuracy**

---

## 🎯 Objectives

- Analyze and explore the Crop Recommendation dataset
- Perform data preprocessing and data cleaning
- Apply feature scaling using **MinMaxScaler**
- Train and compare **7 Machine Learning models**
- Explain model predictions using **SHAP** and **LIME**
- Deploy the best-performing model using **Streamlit**

---

## 📂 Dataset

| Feature | Description | Unit |
|---------|-------------|------|
| N | Nitrogen content in soil | kg/ha |
| P | Phosphorus content in soil | kg/ha |
| K | Potassium content in soil | kg/ha |
| Temperature | Average temperature | °C |
| Humidity | Relative humidity | % |
| pH | Soil acidity/alkalinity | 0–14 |
| Rainfall | Annual rainfall | mm |
| Label (Target) | Recommended crop name | — |

### Dataset Summary

- **Total Samples:** 2,200
- **Target Classes:** 22 crop varieties
- **Missing Values:** None
- **Class Distribution:** Balanced (100 samples per crop)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- LightGBM
- SHAP
- LIME
- Streamlit

---

## 🔄 Data Preprocessing Pipeline

```text
Raw Dataset
     │
     ├── Missing Value Check
     ├── Duplicate Removal
     ├── Label Encoding
     ├── Feature Scaling (MinMaxScaler)
     └── Train-Test Split (80% Train / 20% Test)
```

---

## 🤖 Machine Learning Models

| Model | Training Accuracy | Testing Accuracy |
|-------|------------------:|-----------------:|
| Logistic Regression | 98.13% | 95.23% |
| Decision Tree | 100.00% | 98.64% |
| **Random Forest ⭐** | **100.00%** | **99.32%** |
| SVM | 98.13% | 96.14% |
| KNN | 98.98% | 97.05% |
| XGBoost | 100.00% | 98.41% |
| LightGBM | 100.00% | 98.64% |

> ⭐ **Random Forest** was selected as the final model due to its highest testing accuracy and excellent generalization performance.


<img width="1536" height="1024" alt="ChatGPT Image Jun 26, 2026, 10_12_32 AM" src="https://github.com/user-attachments/assets/061a0bf1-f2df-4479-9709-e91f9efbff38" />

## 📊 Results

- Best Model: **Random Forest**
- Testing Accuracy: **99.32%**
- Successfully compared seven Machine Learning models.
- Built an interactive **Streamlit** web application for real-time crop prediction.
- Used **SHAP** and **LIME** to improve model interpretability.

---

## 👩‍💻 Author

**Fatima Hafeez**  
Data Science Student

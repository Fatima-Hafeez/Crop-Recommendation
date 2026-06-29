# Crop-Recommendation
Crop-Recommendation

🌾 Crop Recommendation System Using Machine Learning

📌 Project Overview

This project applies Machine Learning to solve a real-world agricultural problem — recommending the optimal crop based on soil and environmental conditions. By analyzing features such as soil nutrients, temperature, humidity, pH, and rainfall, the system helps farmers make data-driven decisions to maximize yield.

Best Model: Random Forest with 99.32% Testing Accuracy

🎯 Objectives

✅ Analyze and explore the Crop Recommendation dataset

✅ Perform thorough data preprocessing and cleaning

✅ Apply feature scaling using MinMaxScaler

✅ Train and compare 7 Machine Learning models

✅ Explain predictions using SHAP and LIME

✅ Deploy the best model via an interactive Streamlit web app

📂 Dataset

FeatureDescriptionUnit

N

Nitrogen content in soil

kg/ha

P

Phosphorus content in soil

kg/ha

K

Potassium content in soil

kg/ha

Temperature

Average temperature

°C

Humidity

Relative humidity

%

pH

Soil acidity/alkalinity

0–14

Rainfall

Annual rainfall

mm

Label (Target)

Recommended crop name

—

Total Samples: 2,200

Target Classes: 22 crop varieties

Missing Values: None

Class Balance: Uniform (100 samples per crop)

🛠 Technologies Used

Python · Pandas · NumPy · Matplotlib · Seaborn
Scikit-learn · XGBoost · LightGBM · SHAP · LIME · Streamlit


🔄 Data Preprocessing Pipeline

Raw Data
   │
   ├── Missing Value Check       → No missing values found
   ├── Duplicate Removal         → Cleaned
   ├── Label Encoding            → 22 crop labels → numeric
   ├── Feature Scaling           → MinMaxScaler (0 to 1)
   └── Train-Test Split          → 80% Train / 20% Test


🤖 Machine Learning Models

Seven models were trained and evaluated:

ModelTraining AccuracyTesting Accuracy

Logistic Regression

98.13%

95.23%

Decision Tree

100.00%

98.64%

Random Forest ⭐

100.00%

99.32%

SVM

98.13%

96.14%

KNN

98.98%

97.05%

XGBoost

100.00%

98.41%

LightGBM

100.00%

98.64%

⭐ Random Forest selected as the final model for deployment based on highest testing accuracy and strong generalization.
<img width="1536" height="1024" alt="ChatGPT Image Jun 26, 2026, 10_12_32 AM" src="https://github.com/user-attachments/assets/e34fdac0-1b41-4636-be3c-177959f6f0f4" />

👩‍💻 Author

Fatima HafeezData Science Student


---
# ❤️ Heart Attack Prediction using Machine Learning

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11+-blue?style=for-the-badge\&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge\&logo=jupyter)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?style=for-the-badge\&logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge\&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge\&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</p>

---

# 📖 Project Overview

Cardiovascular diseases remain one of the leading causes of death worldwide. Early identification of individuals at risk enables healthcare professionals to recommend preventive measures and improve patient outcomes.

This project develops a complete **Machine Learning pipeline** for predicting **Heart Attack Risk** using patient medical records. The workflow covers everything from raw data preprocessing to feature engineering, exploratory data analysis, handling class imbalance, model training, evaluation, and prediction.

The objective is to demonstrate an end-to-end machine learning solution following industry-standard practices.

---

# 🚀 Project Highlights

* ✅ Complete Data Cleaning Pipeline
* ✅ Feature Engineering
* ✅ Blood Pressure Feature Extraction
* ✅ One-Hot Encoding
* ✅ Label Encoding
* ✅ Exploratory Data Analysis (EDA)
* ✅ Correlation Analysis
* ✅ Feature Selection
* ✅ Class Imbalance Handling
* ✅ Feature Scaling
* ✅ Machine Learning Model Training
* ✅ Performance Evaluation
* ✅ Prediction of Heart Attack Risk

---

# 🧠 Machine Learning Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Encoding
      │
      ▼
Correlation Analysis
      │
      ▼
Feature Selection
      │
      ▼
Handling Class Imbalance
(RandomOverSampler)
      │
      ▼
Feature Scaling
(MinMaxScaler)
      │
      ▼
Train/Test Split
      │
      ▼
Model Training
      │
      ▼
Performance Evaluation
      │
      ▼
Heart Attack Risk Prediction
```

---

# 📂 Project Structure

```text
Heart_Attack_Prediction/
│
├── Heart_Attack_prediction.ipynb
├── heart_attack_prediction_dataset.csv
├── heart_attack_prediction_dataset_after_cleaning.csv
├── README.md
└── requirements.txt
```

---

# 📊 Dataset Information

The dataset contains multiple medical and lifestyle attributes including:

* Age
* Gender
* Cholesterol
* Blood Pressure
* Heart Rate
* Diabetes
* Smoking
* Obesity
* Alcohol Consumption
* Exercise Hours
* Diet
* Previous Heart Problems
* Medication Usage
* Stress Level
* BMI
* Triglycerides
* Physical Activity
* Sleep Hours
* Country

**Target Variable**

```
Heart Attack Risk

0 → Low Risk
1 → High Risk
```

---

# 🛠 Data Preprocessing

The notebook performs extensive preprocessing before training the model.

### ✔ Data Cleaning

* Duplicate removal
* Missing value verification
* Data type validation

### ✔ Feature Engineering

Several features were transformed into machine-learning-friendly formats.

Examples include:

* Blood Pressure

```
158/88

↓

Systolic Pressure = 158
Diastolic Pressure = 88
```

* Gender

```
Male → 1
Female → 0
```

* Diet

```
Healthy
Average
Unhealthy

↓

2
1
0
```

---

# 📈 Exploratory Data Analysis

The project includes various visualization techniques such as:

* Pie Charts
* Feature Distribution
* Correlation Heatmap
* Category Plots
* Count Plots
* Statistical Summary
* Feature Relationship Analysis

These visualizations help identify important predictors influencing heart attack risk.

---

# ⚖ Handling Imbalanced Data

The original dataset contains significantly more low-risk samples than high-risk samples.

To improve model learning, the dataset is balanced using:

* **RandomOverSampler**
* **MinMaxScaler**

This helps reduce prediction bias and improves model generalization.

---

# 🤖 Machine Learning

The project follows the standard supervised machine learning workflow:

* Data Preparation
* Feature Selection
* Data Scaling
* Model Training
* Prediction
* Performance Evaluation

---

# 📏 Evaluation Metrics

The trained model can be evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC-AUC Score

---

# 💻 Tech Stack

| Category         | Technologies        |
| ---------------- | ------------------- |
| Programming      | Python              |
| Notebook         | Jupyter Notebook    |
| Data Analysis    | Pandas, NumPy       |
| Visualization    | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn        |
| Data Balancing   | imbalanced-learn    |
| Feature Scaling  | MinMaxScaler        |

---

# 🎯 Learning Outcomes

Through this project, I gained practical experience in:

* Data Cleaning
* Feature Engineering
* Data Visualization
* Machine Learning Pipelines
* Class Imbalance Handling
* Feature Scaling
* Medical Data Analysis
* Model Evaluation
* Predictive Analytics

---

# 🔮 Future Improvements

* Hyperparameter Tuning
* Cross Validation
* Ensemble Models
* XGBoost / LightGBM
* Model Explainability (SHAP)
* Streamlit Web Application
* Flask/FastAPI Deployment
* Docker Support
* CI/CD Pipeline
* Cloud Deployment (AWS/Azure)

---

# 👨‍💻 Author

**Developed by Tejas Vishnu Mantena**

### Connect with me

* 🔗 GitHub: https://github.com/TejasVishnuMantena
* 💼 LinkedIn: https://www.linkedin.com/in/tejas-vishnu-mantena

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

Your support motivates me to build more Machine Learning and AI projects.

---


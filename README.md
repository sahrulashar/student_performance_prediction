# 🎓 Student Performance Prediction Using Multiple Linear Regression

## 📖 Overview

This project aims to predict student performance scores using Multiple Linear Regression.

The model is trained using several factors that may influence academic performance, such as:

- Study Hours
- Previous Scores
- Extracurricular Activities
- Sleep Hours
- Practice Papers Solved

The project demonstrates a complete Machine Learning workflow, starting from data preprocessing to model evaluation and prediction.

---

## 🎯 Objectives

- Understand the Machine Learning workflow.
- Perform Exploratory Data Analysis (EDA).
- Clean and preprocess data.
- Train a Multiple Linear Regression model.
- Evaluate model performance using regression metrics.
- Predict student performance based on input features.

---

## 📊 Dataset

Dataset Source:
Student Performance Dataset

### Features

| Feature | Description |
|----------|-------------|
| Hours Studied | Number of study hours |
| Previous Scores | Previous academic scores |
| Extracurricular Activities | Participation in extracurricular activities |
| Sleep Hours | Average sleeping hours |
| Sample Question Papers Practiced | Number of practice papers completed |

### Target

| Target |
|----------|
| Performance Index |

---

## 🔍 Exploratory Data Analysis

The following analyses were performed:

- Dataset Overview
- Missing Value Checking
- Duplicate Data Checking
- Statistical Summary
- Correlation Analysis
- Feature Importance Analysis
- Data Visualization

---

## ⚙️ Data Preprocessing

Steps performed:

1. Data Cleaning
2. Handling Missing Values
3. Removing Duplicate Records
4. Feature Selection
5. Train-Test Split
6. Feature Scaling (MinMaxScaler)

---

## 🤖 Machine Learning Model

Algorithm used:

- Multiple Linear Regression

Libraries:

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

## 📈 Model Evaluation

Evaluation metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

Example Results:

| Metric | Value |
|----------|----------|
| MAE | 1.69 |
| MSE | 4.49 |
| RMSE | 2.11 |

> Results may vary depending on train-test split and preprocessing techniques.

---

## 🚀 Project Workflow

```text
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Exploratory Data Analysis
   │
   ▼
Feature Selection
   │
   ▼
Train Test Split
   │
   ▼
Feature Scaling
   │
   ▼
Model Training
   │
   ▼
Model Evaluation
   │
   ▼
Prediction
```

---

## 📂 Project Structure

```text
student-performance-prediction/
│
├── data/
│   └── Student_Performance.csv
│
├── notebooks/
│   └── students_performance.ipynb
│
├── images/
│   └── visualizations
│
├── models/
│   └── model.pkl
│
├── requirements.txt
│
└── README.md
```

---

## 🛠️ Installation

Clone repository:

```bash
git clone https://github.com/sahrulashar/Student_Performance_Prediction.git
```

Move into project directory:

```bash
cd Student_Performance_Prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## 💡 Future Improvements

- Hyperparameter Optimization
- Model Comparison
- Flask Deployment
- Streamlit Dashboard
- Model Serialization using Pickle

---

## 👨‍💻 Author

Sahrul Ashar

Aspiring Machine Learning Engineer

GitHub:
https://github.com/sahrulashar

---

⭐ If you found this project useful, don't forget to give it a star.

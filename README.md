# 🩺 Diabetes Prediction with PySpark | Scalable ML Pipeline

An end-to-end machine learning project for predicting diabetes using **PySpark MLlib**. This project demonstrates how to build a scalable and efficient machine learning pipeline using distributed computing techniques.

---

## 📌 Project Overview

With the increasing volume of healthcare data, scalable machine learning solutions are essential. In this project, we use PySpark to build a classification model that predicts diabetes outcomes based on patient health data.

The dataset includes key medical features such as:

* Glucose level
* Blood pressure
* BMI (Body Mass Index)
* Insulin level
* Age

✔ Dataset size: 768 observations
✔ Problem type: Binary Classification
✔ Framework: PySpark MLlib

---

## 🎯 Objective

To develop a scalable machine learning pipeline that accurately predicts whether a patient has diabetes using distributed data processing.

---

## ⚙️ Tech Stack

* Python
* PySpark (MLlib)
* Pandas
* NumPy

---

## 🔄 Workflow

1. Spark Session Initialization
2. Data Loading using PySpark
3. Feature Engineering using `VectorAssembler`
4. Train-Test Split
5. Model Training using Logistic Regression
6. Model Evaluation using BinaryClassificationEvaluator

---

## 📊 Model Performance

* Model: Logistic Regression
* Evaluation Metric: AUC
* Score: **0.85**

---

## 📈 Key Insights

* Logistic Regression provides a strong baseline for classification
* Feature transformation using VectorAssembler simplifies ML pipelines
* PySpark enables scalable processing for large datasets

---

## 🚀 How to Run

### 1. Clone the repository

```bash id="sdd4jw"
git clone https://github.com/your-username/diabetes-prediction-pyspark-ml-pipeline.git
cd diabetes-prediction-pyspark-ml-pipeline
```

### 2. Install dependencies

```bash id="2qv22y"
pip install pyspark pandas numpy
```

### 3. Run script / notebook

```bash id="9r7nh4"
python main.py
```

or

```bash id="rflpf9"
jupyter notebook
```

---

## 📂 Project Structure

```id="gbyfb8"
├── data/
├── notebooks/
│   └── pyspark_diabetes.ipynb
├── src/
│   └── main.py
├── README.md
└── requirements.txt
```

## ⭐ If you found this project useful, feel free to star the repository!

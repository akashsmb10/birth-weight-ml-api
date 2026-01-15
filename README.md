# ML-Driven Clinical Prediction System with RESTful APIs

A Machine Learning–powered web application that predicts **newborn birth weight** based on maternal and pregnancy-related factors.  
The application is built using **Python, Flask, and Scikit-learn** and deployed live using **Render**.

---

## 🚀 Live Demo
🔗 https://birth-weight-predictor-akt3.onrender.com

---

## 📌 Project Objectives

The main goals of this project are:

- Understand clinical data-based regression problems
- Perform data preprocessing and feature selection
- Train a regression model using Scikit-learn
- Evaluate model performance using standard metrics
- Serialize and load models using Pickle
- Build RESTful APIs using Flask
- Deploy ML models as real-world web services

---

## 📂 Project Structure

```
Machine Model/
│
├── birth-weight-predictor/
│   ├── app.py
│   ├── model.pkl
│   ├── requirements.txt
│   └── .gitignore
│
├── templates/
│   └── index.html
│
├── dataset/
│   └── birth_weight.csv
│
├── ML_training.ipynb
├── model_training.ipynb
└── myvenv/

```

---

## 📊 Dataset

The dataset consists of structured maternal and pregnancy health records.

### Features

- Gestation (days)
- Parity
- Mother Age
- Mother Height
- Mother Weight
- Smoking Status (0 = No, 1 = Yes)

### Target Variable

- **Birth Weight (grams)**

---

## 🤖 Machine Learning Model

- Model Type: Supervised Regression
- Library: Scikit-learn
- Preprocessing applied before training
- Model saved using `pickle` as `model.pkl`

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Flask
- HTML / CSS
- Jupyter Notebook
- Postman (for API testing)

---
## 🔄 Development Workflow
- Data Analysis: ML_training.ipynb
- Model Training: model_training.ipynb
- Application Development: app.py
- Testing: Local server + Postman

Deployment: Render platform
---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/akashsmb10/birth-weight-ml-api.git
cd birth-weight-ml-api
```




# 🧠 Birth Weight Prediction – ML-Driven Clinical Prediction System

This project implements a **Machine Learning–based regression model** using Python to predict **newborn birth weight** based on maternal and pregnancy-related clinical features.  
The trained model is deployed using **Flask REST APIs** and can be accessed via both **HTTP requests and a simple web interface**.

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

'''Machine Model/
│
├── templates/
│ └── index.html
│
├── dataset/
│ └── birth_weight.csv
│
├── app.py
├── model.pkl
├── ML_training.ipynb
├── model_training.ipynb
├── requirements.txt
├── .gitignore'''

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

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/akashsmb10/birth-weight-ml-api.git
cd birth-weight-ml-api

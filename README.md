# ML-Driven Clinical Prediction System with RESTful APIs

A Machine Learning–powered web application that predicts **newborn birth weight** based on maternal and pregnancy-related factors.  
The application is built using **Python, Flask, and Scikit-learn** and deployed live using **Render**.

---

## 🚀 Live Demo
🔗 https://birth-weight-predictor-akt3.onrender.com

---

## 🧠 Problem Statement
Low or abnormal birth weight is a critical indicator of neonatal health.  
This project aims to provide a **data-driven estimation** of birth weight using clinical inputs such as:
- Gestation period
- Parity
- Mother’s age
- Height and weight
- Smoking status

---

## 🛠️ Tech Stack
- **Programming Language:** Python  
- **Backend:** Flask  
- **Machine Learning:** Scikit-learn  
- **Frontend:** HTML, CSS  
- **Deployment:** Render  
- **Version Control:** Git & GitHub  

---

## 📊 Machine Learning Model
- Supervised regression model trained on structured medical data  
- Feature preprocessing and validation handled before prediction  
- Model serialized using `pickle` for deployment  
- Model performance evaluated using standard regression metrics  

---

## 🔌 REST API
The application exposes a RESTful endpoint for predictions:

- **Endpoint:** `/predict`  
- **Method:** `POST`  
- **Input:** JSON payload containing clinical features  
- **Output:** Predicted birth weight (in grams)

Basic request validation and error handling are implemented to ensure reliable API responses.

---

## ⚙️ Features
- Clean and simple UI for clinical data input  
- Real-time birth weight prediction  
- End-to-end ML pipeline (training → inference → deployment)  
- Fully deployed and publicly accessible web application  

---

## 🧪 Testing
- Manual API testing performed using Postman  
- Input validation tested for missing and invalid values  
- Output sanity checks conducted during development  

---

## 📁 Project Structure
birth-weight-predictor/
- ├── app.py
- ├── model.pkl
- ├── requirements.txt
- ├── templates/
- └── README.md

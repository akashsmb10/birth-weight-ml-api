# 👶 Birth Weight Prediction Web App

A Machine Learning powered web application that predicts **newborn birth weight** based on maternal and pregnancy-related factors.  
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
- Height & weight
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
- Model trained on structured medical data
- Regression-based approach
- Model serialized using `pickle`
- Input validation handled via Flask routes

---

## ⚙️ Features
- Clean and simple UI for data input
- Real-time birth weight prediction
- End-to-end ML pipeline (training → deployment)
- Fully deployed and accessible online

---

## 📁 Project Structure
- birth-weight-predictor/
--├── app.py              
--├── model.pkl           
--├── requirements.txt   
--├── templates/          
--└── README.md           

---

## 🧪 How to Run Locally
```bash
git clone https://github.com/akashsmb10/birth-weight-predictor.git
cd birth-weight-predictor
pip install -r requirements.txt
python app.py


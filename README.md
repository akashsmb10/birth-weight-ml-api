🧠 Birth Weight Prediction System using Machine Learning & Flask REST APIs

This project is an end-to-end Machine Learning web application that predicts newborn birth weight using maternal and pregnancy-related clinical features.
It demonstrates how a trained ML model can be deployed using Flask REST APIs and accessed via both HTTP requests and a simple web interface.

🚀 Key Features

Machine Learning–based regression model for birth weight prediction

Flask REST API for real-time predictions

HTML form-based frontend for user input

Input validation and error handling

Trained model loaded using Pickle

Deployment-ready structure (Render compatible)

📌 Problem Statement

Birth weight is a critical indicator of neonatal health.
This application estimates birth weight using clinical and demographic maternal factors, enabling data-driven healthcare insights and demonstrating practical ML deployment using RESTful APIs.

🧱 Project Structure
'''
Machine Model/
├── templates/
│ └── index.html
├── dataset/
│ └── birth_weight.csv
├── myvenv/
├── app.py
├── model.pkl
├── ML_training.ipynb
├── model_training.ipynb
├── requirements.txt
├── .gitignore
└── README.md
'''

📊 Dataset Description

The dataset consists of structured pregnancy and maternal health records.

Input Features

Gestation (days)

Parity

Mother’s Age

Mother’s Height

Mother’s Weight

Smoking Status (0 = No, 1 = Yes)

Target Variable

Birth Weight (grams)

🤖 Machine Learning Pipeline

Data cleaning and preprocessing

Feature selection and formatting

Regression model training using Scikit-learn

Model evaluation using regression metrics

Final model serialized using pickle as model.pkl

📈 Evaluation Metrics

R² Score

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

🔌 REST API Usage
Endpoint

POST /predict

Sample Request (JSON)

{
"gestation": 280,
"parity": 1,
"age": 26,
"height": 160,
"weight": 60,
"smoking": 0
}

Sample Response

{
"predicted_birth_weight": 3120.45
}

🛠️ Technologies Used

Python

Flask

Scikit-learn

Pandas

NumPy

HTML / CSS

Jupyter Notebook

Postman

Git & GitHub

⚙️ Local Setup Instructions
Clone Repository

git clone https://github.com/akashsmb10/birth-weight-ml-api.git

cd birth-weight-ml-api

Create Virtual Environment

python -m venv myvenv
myvenv\Scripts\activate (Windows)
source myvenv/bin/activate (Linux/Mac)

Install Dependencies

pip install -r requirements.txt

Run Application

python app.py

Open in browser:
http://127.0.0.1:5000

🧪 Testing

API tested using Postman

UI tested through browser forms

Error handling tested for invalid inputs

Prediction sanity checks performed

🚀 Deployment

The project is ready for deployment on cloud platforms such as:

Render

Railway

Heroku (with configuration changes)

Render Start Command

gunicorn app:app

🔮 Future Enhancements

Add feature scaling pipelines

Improve UI with Bootstrap

Add logging and monitoring

Add Docker support

Add Swagger API documentation

👤 Author

Akash Bailwad
Data Analytics | Machine Learning | Backend Development
GitHub: https://github.com/akashsmb10

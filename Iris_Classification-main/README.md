🌸 Iris Classification Web App

A simple Machine Learning web application built using Streamlit that predicts the species of an Iris flower based on user input features.
The model and scaler are loaded from pre-trained pickle files.

🚀 Features

User-friendly web interface using Streamlit

Accepts four input parameters:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

Uses a pre-trained ML model for prediction

Input validation for numeric values

Instant prediction output

🧠 Machine Learning Details

Dataset: Iris Dataset

Preprocessing: StandardScaler

Model: Trained ML classification model (loaded via model.pkl)

Scaler: Loaded via scaler.pkl

📂 Project Structure
├── app.py
├── model.pkl
├── scaler.pkl
├── requirements.txt
└── README.md

🛠️ Tech Stack

Python

Streamlit

NumPy

Scikit-learn

Pickle

▶️ How to Run the App Locally

Clone the repository

git clone https://github.com/your-username/iris-classification-streamlit.git
cd iris-classification-streamlit


Install dependencies

pip install -r requirements.txt


Run the Streamlit app

streamlit run app.py

📦 requirements.txt
streamlit
numpy
scikit-learn

# iris flower 

## 🌸 Iris Flower Prediction Web App

A simple and interactive Machine Learning web application built using Streamlit that predicts the species of an Iris flower based on user-provided measurements.

## 📌 Project Description

The Iris Flower Prediction Web App allows users to input flower measurements such as:

Sepal Length

Sepal Width

Petal Length

Petal Width

These values are scaled using a pre-trained scaler and passed to a trained Machine Learning model to predict the Iris flower species in real time.

This project is ideal for beginners who want to understand how to deploy ML models using Streamlit.

## 🛠️ Tech Stack

🐍 Python

🎨 Streamlit

📊 NumPy

🤖 Scikit-learn

📦 Pickle

## ✨ Features

Interactive user interface built with Streamlit

Custom UI styling using CSS

Real-time Iris flower prediction

Pre-trained Machine Learning model

Scaler and model loaded using Pickle

Simple and user-friendly input fields


## ⚙️ How It Works

User enters flower measurements through the UI.

Input values are converted into a NumPy array.

Data is scaled using a pre-trained scaler.

Scaled data is passed to the ML model.

Model predicts the Iris flower species.

Prediction is displayed on the web interface.

## 💻 Installation & Setup
1️⃣ Clone the Repository

2️⃣ Create a Virtual Environment (Optional)
python -m venv venv
source venv/bin/activate    # Windows: venv\Scripts\activate

3️⃣ Install Dependencies
pip install streamlit numpy scikit-learn

4️⃣ Run the Streamlit App
streamlit run app.py

## ▶️ Usage

Run the Streamlit app using the command above

Enter flower measurements

Click Predict

View the predicted Iris flower species

## 📊 Output

The application predicts one of the following Iris species:

🌼 Iris Setosa

🌺 Iris Versicolor

🌸 Iris Virginica

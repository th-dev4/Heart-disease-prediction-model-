# 🫀 Heart Disease Prediction Model

This project is a **Machine Learning-based web application** that predicts the likelihood of a person having heart disease based on medical input data. It provides a simple, user-friendly interface where users can enter various health metrics and receive predictions powered by trained ML models.

## 🚀 Features

- 💻 Built with **Python, Streamlit**
- 🧠 Uses **Random Forest** and **ANN (Artificial Neural Network)** for prediction
- 🩺 Inputs: age, sex, cholesterol, resting BP, fasting blood sugar, etc.
- 📈 Trained and tested on publicly available heart disease datasets
- 📊 Real-time prediction output
- ☁️ Deployable locally or on cloud platforms

## 🛠️ Tech Stack

- **Frontend:** Streamlit
- **Backend:** Python
- **Machine Learning Models:** 
  - Random Forest
  - Artificial Neural Network (ANN)
- **Libraries:** scikit-learn, TensorFlow, pandas, numpy

## 🧪 How It Works

1. User enters medical parameters through the web interface
2. The data is preprocessed and passed to a trained model
3. The model predicts whether the person is at risk of heart disease
4. The result is displayed instantly

## 🧬 Input Features

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Rest ECG
- Max Heart Rate
- Exercise Induced Angina
- Oldpeak
- Slope
- CA (number of major vessels)
- Thalassemia

## 📂 Folder Structure

```bash
heart-disease-prediction-model/
│
├── app.py                  # Main Streamlit app
├── rf_model.pkl            # Random Forest model file
├── ann_model.h5            # ANN model (optional)
├── heart.csv               # Dataset used for training
├── requirements.txt        # Python dependencies
└── .gitignore              # Git ignored files (like venv/)




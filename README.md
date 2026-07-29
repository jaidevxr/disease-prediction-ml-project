# Disease Prediction — ML Project

> 🏥 **Predict diseases from symptoms** using machine learning — a Streamlit web app powered by trained classifiers for medical symptom analysis.

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python)](https://python.org)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?style=flat-square&logo=streamlit)](https://streamlit.io)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?style=flat-square&logo=scikit-learn)](https://scikit-learn.org)

## What is this?

A **disease prediction system** that takes user-reported symptoms as input and predicts possible diseases using trained ML classifiers. The project includes data cleaning, feature engineering, model training, and a Streamlit web interface for easy interaction.

## Features

- 🩺 **Symptom-Based Prediction** — select symptoms and get disease predictions
- 🤖 **Multiple ML Models** — trained and compared for best accuracy
- 📊 **Data Pipeline** — full data cleaning and preprocessing notebook
- 🖥️ **Web App** — interactive Streamlit interface

## Tech Stack

- **ML**: Scikit-Learn (Classification)
- **Web App**: Streamlit
- **Language**: Python
- **Data**: Medical symptom-disease dataset

## Getting Started

```bash
git clone https://github.com/jaidevxr/disease-prediction-ml-project.git
cd disease-prediction-ml-project
pip install -r requirements.txt  # if available
streamlit run app.py
```

## Project Structure

```
├── app.py                             # Streamlit web application
├── data_cleaning_and_modeling.ipynb   # Data preprocessing + model training
├── data/                              # Training datasets
├── saved_models/                      # Pre-trained model files
└── README.md
```

## License

MIT

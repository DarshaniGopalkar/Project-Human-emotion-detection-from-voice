# 🎤 Human Emotion Detection from Voice

A Streamlit-based web application that detects human emotions from voice recordings using MFCC feature extraction and a trained machine learning model.


## 📌 Project Overview

This project aims to identify human emotions (like happy, sad, angry, etc.) based on speech signals. It leverages:
- **Audio feature extraction** using `librosa`
- **Machine learning** for classification
- **Streamlit** for a user-friendly web interface


## 🚀 Features

- 🎙 Record your voice live via microphone
- 📁 Upload `.wav` audio files
- 📊 Extract MFCC features from audio
- 🤖 Predict emotion using a trained model
- 📈 Real-time feedback and prediction

## 🛠 Tools & Libraries

- `Python`
- `Streamlit`
- `Librosa`
- `SoundDevice`
- `Scikit-learn`
- `NumPy`, `Pandas`

---

## 📁 Project Structure

app.py # Streamlit web app
model.pkl # Trained emotion detection model
audio_utils.py # Feature extraction functions
requirements.txt # Required Python libraries
README.md # Project documentation
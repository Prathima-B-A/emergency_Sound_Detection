# 🚨 Emergency Sound Detection using Deep Learning

This project detects **emergency sounds** such as explosions, fire alarms, gunshots, and human screams using a **CNN-based sound classification model**.  
It employs **Mel-spectrogram feature extraction** and **deep learning** to classify critical sound events that could indicate emergency situations.

---

## 🎯 Project Objective
To develop a reliable sound classification system capable of distinguishing between emergency and non-emergency sounds to enhance safety and automated alert systems.

---

## 📂 Dataset
The dataset consists of the following categories:
- **Explosion dataset/**
- **Fire/**
- **GunShots/**
- **Scream/**
- **Non_scream/**

Each folder contains `.wav` audio samples used for training and testing.

---

## 🧠 Model Architecture
The model is a hybrid **CNN and BiGRU hybrid neural network** designed to process Mel-spectrograms extracted from audio signals.  
Key layers include:
- Convolutional layers for feature extraction  
- MaxPooling layers for dimensionality reduction  
- Dense layers for classification  

---

## 🧮 Feature Extraction
Mel-spectrograms are generated using **Librosa**, converting raw audio into a visual time–frequency representation suitable for CNN processing.

---
The dataset used in this project can be accessed here:  
👉 [Google Drive Link](https://drive.google.com/drive/folders/18UOrBO5EAM8e_Ykyg9Ok_DBPxszvQV1d?usp=drive_link)## 🧰 Requirements

Install dependencies using:
```bash
pip install -r requirements.txt

# Facial Emotion Detection

## Overview
Facial Emotion Detection is a machine learning-based project that detects human emotions from facial expressions using deep learning and computer vision.  
This project uses a **Convolutional Neural Network (CNN)** model trained on facial images to classify emotions such as **Happy**, **Sad**, **Angry**, **Surprise**, and **Neutral**.  
The system is implemented in **Python** using **Flask** as the backend framework.

---

## Objectives
- To detect human emotions in real-time using webcam input.  
- To implement a deep learning model for emotion classification.  
- To integrate the trained model with Flask for real-time prediction.

---

## Technologies Used
- **Programming Language:** Python  
- **Framework:** Flask  
- **Libraries:**  
  - OpenCV  
  - TensorFlow  
  - Keras  
  - NumPy  

---

## Features
- Real-time facial emotion detection using webcam.  
- Uses a trained CNN model for classification.  
- Displays detected emotion labels on live video feed.  
- Lightweight and easy to run locally.  

---

## Project Structure
Facial-Emotion-Detection/
│
├── app.py # Flask backend
├── facialemotionmodel.json # Model architecture
├── facialemotionmodel.h5 # Trained model weights
├── requirements.txt # Python dependencies
└── README.md # Project documentation

## How to Run the Project

### Step 1: Clone the Repository

git clone https://github.com/janvikale2005/Facial-Emotion-Detection.git
cd Facial-Emotion-Detection

Step 2: Install Dependencies

Make sure Python 3.8+ is installed, then run:

pip install -r requirements.txt


If you don’t have requirements.txt, manually install:

pip install flask tensorflow keras opencv-python numpy

Step 3: Run the Flask Application
python app.py

Step 4: Open in Browser

Open the following link in your browser:

http://127.0.0.1:5000/

Model Files

facialemotionmodel.json: Contains the CNN model architecture.

facialemotionmodel.h5: Contains the trained model weights.

Output

Captures live webcam feed using OpenCV.

Detects the user’s face.

Predicts and displays emotion labels in real-time such as:

Happy
Sad
Angry
Surprise
Neutral
Disgust

Requirements File

Here’s what to include in your requirements.txt:

Flask==3.0.0
tensorflow==2.15.0
keras==2.15.0
opencv-python==4.9.0.80
numpy==1.26.0

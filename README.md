**Facial Emotion Recognition & Song Recommendation System**

An intelligent system that captures facial expressions in real-time, detects emotional states using deep learning models (CNN + LSTM), and recommends songs tailored to the user's mood.

**Overview**

This project combines computer vision and deep learning to recognize emotions from facial expressions and recommends music accordingly to enhance user experience and emotional well-being.

**Features**

1. Real-time facial emotion detection via webcam using OpenCV
2. Emotion classification with CNN + LSTM deep learning models (88.84% accuracy)
3. Personalized music recommendation mapped to emotion categories
3. Built with Python and powerful ML/DL libraries for efficient inference
   
**Tech Stack**
1. Python
2. OpenCV
3. TensorFlow / Keras
4. CNN + LSTM
5. NumPy, Pandas, Matplotlib (for data handling and visualization)
   
**Project Structure**
1. emotion_model.h5: Trained deep learning model
2. realtime.py: Script for real-time emotion detection
3. recommend.py: Logic for emotion-based music recommendation
4. utils/: Helper functions and preprocessing scripts
5. dataset/: Facial expression image dataset used for training

**How to Run**
1. Clone this repository
2. Install dependencies:
3. pip install -r requirements.txt
4. Run the application:
5. python realtime.py

Ensure your system has access to a webcam for real-time detection.

Emotions Supported
1. Happy
2. Sad
3. Angry
4. Neutral
5. Surprise
6. Fear

**Music Mapping**

Each emotion is mapped to a playlist or set of songs using pre-defined logic or APIs (e.g., Spotify or local file system).

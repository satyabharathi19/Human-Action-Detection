# Human Action Detection Using Deep Learning 📹

## Overview
This project aims to develop a Human Action Detection system using deep learning techniques. The model can detect violent actions such as Punch, PushUps, and everyday activities like WalkingWithDog and more.

## Project Goal
To create a reliable alert system that can automatically identify potentially harmful actions in real-time and notify authorities, aiming to ensure timely intervention and improve safety.

## Key Features
- Detects and classifies human actions from videos.
- Achieves an accuracy of **91.16%** on the validation dataset.
- Real-time action detection using video feed or pre-recorded videos.
- Deployed using **Streamlit** for user-friendly interaction.

## Dataset
The dataset includes various human action videos categorized into four main classes:
- WalkingWithDog
- Punch
- PushUps
- Biking

## Data Preprocessing
The video frames are resized, normalized, and fed into a CNN + LSTM model for processing. The labels are one-hot encoded for multi-class classification.

## Model Architecture
The model combines:
- **Convolutional Neural Network (CNN)**: For spatial feature extraction from video frames.
- **Long Short-Term Memory (LSTM)**: For capturing temporal dependencies across sequences of frames.
- **Softmax Output Layer**: For multi-class classification of actions.

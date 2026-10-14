# EEG-Based Drowsiness Detection Using Signal Processing and Edge AI

## Overview
This project classifies EEG signals into Awake and Drowsy states using signal preprocessing and a convolutional neural network (CNN).

## Key Features
- EEG signal filtering and normalization
- Four-second window segmentation with 50% overlap
- Binary Awake/Drowsy classification
- CNN model training and evaluation
- TensorFlow Lite model preparation for Raspberry Pi

## Technologies
Python, NumPy, EEG Signal Processing, CNN, TensorFlow Lite, Raspberry Pi

## Model Performance
Current evaluation accuracy: approximately 71.2%.

## Deployment Status
The TensorFlow Lite model and preprocessing parameters have been prepared for Raspberry Pi deployment. Real-time EEG hardware integration is not yet implemented.

## Repository Contents
- `notebooks/`: Training and evaluation notebook
- `models/`: TensorFlow Lite model
- `preprocessing/`: Saved preprocessing parameters
- `config/`: Classification threshold settings
- `results/`: Evaluation metrics and plots

## How to Run
Open the notebook in Google Colab and follow the cells in order. Install the required packages listed in `requirements.txt` before running the code.

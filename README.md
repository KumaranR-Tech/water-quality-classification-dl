# Water Quality Classification using Deep Learning

## Overview
Developed a deep learning model to classify water types (Tap, Soap, Drain) using sensor-based parameters such as Electrical Conductivity (EC), pH, and Total Dissolved Solids (TDS).

## Dataset
- Total samples: 10,800
- Features:
  - EC value (ms/cm)
  - pH value
  - TDS value (ppm)
- Classes: 3 (Tap Water, Soap Water, Drain Water)

## Model Architecture
- Dense Neural Network
- Dense (64) + ReLU
- Batch Normalization
- Dropout (0.3)
- Dense (32) + ReLU
- Dropout (0.3)
- Output Layer (Softmax)

## Technologies Used
- Python
- TensorFlow / Keras
- Scikit-learn
- NumPy, Pandas

## Performance
- Accuracy: 99.5%
- Strong generalization using BatchNorm & Dropout

## Features
- End-to-end ML pipeline
- Real-time prediction capability for IoT systems

## Author
Kumaran R
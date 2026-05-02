# Water Quality Classification using Deep Learning

## Project Overview
This project presents a deep learning-based classification system that identifies water quality types (Tap Water, Soap Water, Drain Water) using sensor-based parameters.

The model is designed for real-world IoT applications where water quality monitoring is essential.

---

## Dataset
- Total Samples: 10,800
- Features:
  - Electrical Conductivity (EC)
  - pH Value
  - Total Dissolved Solids (TDS)
- Classes: 3 (Tap, Soap, Drain)

---

## Machine Learning Pipeline
1. Data Preprocessing
2. Label Encoding
3. Feature Scaling
4. Train-Test Split
5. Model Training
6. Evaluation & Visualization

---

## Model Architecture
- Dense (64, ReLU)
- Batch Normalization
- Dropout (0.3)
- Dense (32, ReLU)
- Dropout (0.3)
- Output Layer (Softmax)

---

## Results
- Test Accuracy: **99.5%**
- Strong generalization across all classes
- Minimal overfitting due to BatchNorm & Dropout

---

## Sample Prediction
Input:
[EC = 400, pH = 7.2, TDS = 120]

Output:
Predicted Water Type: Drain Water

---

## Tech Stack
- Python
- TensorFlow / Keras
- Scikit-learn
- NumPy, Pandas, Matplotlib, Seaborn

---

## Future Improvements
- Deploy as web app (Streamlit)
- Integrate with IoT sensors
- Real-time monitoring dashboard

---

## Author
Kumaran R

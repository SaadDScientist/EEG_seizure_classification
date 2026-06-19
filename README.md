# EEG Seizure Classification System

---

## Description
A deep learning project designed to classify epileptic seizure activity using EEG brain signal data.

The system analyzes EEG time-series signals to detect whether a patient is experiencing a seizure or normal brain activity. The goal is to support early detection of epilepsy using machine learning techniques.

---

## Technologies Used
- Python  
- NumPy  
- Pandas  
- SciPy  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib  

---

## Dataset
- EEG Epilepsy Dataset  
- Includes:
  - EDF files (raw EEG recordings)
  - Processed MATLAB files
  - NumPy-formatted signal data  

---

## Preprocessing Steps

- EEG signal cleaning and normalization  
- Feature extraction from:
  - Time-domain signals  
  - Frequency-domain signals  
- Dimensionality reduction using **PCA**  
- Handling class imbalance using **SMOTE**  
- Train-test split for model evaluation  

---

## Models Used

- 1D Convolutional Neural Network (CNN)  
- LSTM (Long Short-Term Memory network) for temporal pattern learning  

---

## Performance Evaluation

The model was evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-score  

Performance was measured on unseen test data after training.


# EEG Signal Analysis for Alzheimer's and FTD Prediction

This project focuses on predicting Alzheimer's disease, Frontotemporal Dementia (FTD), or normal conditions using EEG signal data. The aim is to develop a robust machine learning pipeline for processing EEG signals and achieving accurate predictions.



## Dataset

- **EEG Signals Directory**: `/Users/pro/Desktop/ds004504-1.0.7/derivatives`
- **Participants Information**: `/Users/pro/Desktop/ds004504-1.0.7/participants.tsv`
- **Electrodes Used**: 19 scalp electrodes.

The dataset includes EEG recordings and metadata for participants with Alzheimer's, FTD, and normal conditions.


## Visualizations

### Participant Distribution by Age

![image](https://github.com/user-attachments/assets/46099dd5-7ef6-47c6-9f0d-81feac9f0948)


### Participant Distribution by Group
![image](https://github.com/user-attachments/assets/bba414d7-2caa-43aa-a8cb-42c7df36fdf4)


### Types of Diseases Studied

<img width="910" alt="Screenshot 2024-12-08 at 15 36 41" src="https://github.com/user-attachments/assets/fa464e6e-513d-4d35-a358-481ffd536f9c">


## Project Objectives

1. Develop a preprocessing pipeline for EEG signal data.
2. Extract meaningful features from EEG signals.
3. Implement machine learning models for classification.

## Preprocessing

- Standardized preprocessing techniques, including filtering, normalization, and epoching.
- Applied overlapping windows for better signal segmentation .

## Feature Extraction

- Frequency band analysis (Delta, Theta, Alpha, Beta, Gamma).
- Time-domain and frequency-domain features.
- Dimensionality reduction using autoencoders.

## Models Used

 **Autoencoder + LSTM**:
   - Used to learn representations and temporal patterns in EEG data.


## Results

| Model                  | Accuracy |
|------------------------|----------|
| Autoencoder + LSTM     | 98%      |







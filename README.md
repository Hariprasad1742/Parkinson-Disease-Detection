
# Parkinson's Disease Classification using SVM

## Overview
This project aims to classify individuals as Healthy (0) or having Parkinson’s (1) based on voice features using Support Vector Machines (SVM).

## Dataset
- **Source:** Parkinson’s dataset (195 samples, 23 Parkinson’s patients)  
- **Features:** Voice-based frequency and amplitude variations  
- **Target Column:** `status` (0 = Healthy, 1 = Parkinson’s)  

## Setup & Installation  
### 1. Clone the Repository  

git clone https://github.com/your-repo/parkinsons-classification.git
cd parkinsons-classification

2. Install Dependencies

pip install -r requirements.txt

3. Run the Model

python parkinsons_svm.py





Model Details

    Algorithm: Support Vector Machine (SVM)
    Feature Scaling: StandardScaler
    Hyperparameter Tuning: GridSearchCV
    Evaluation Metrics: Accuracy, Classification Report, Confusion Matrix



Results

    Best SVM Parameters: { 'C': 10, 'gamma': 0.1, 'kernel': 'rbf' }
    Test Accuracy: 91.28%
    Example Prediction:
        Input: Voice feature sample
        Output: "Prediction: Parkinson's Detected (85.32%)"

Visualizations

    Confusion Matrix
    Feature Correlation Heatmap
    Accuracy vs. C Value Line Graph

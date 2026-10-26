# Sonar-Signal-Classification

Classifies sonar signals as ** Rock (R)** or **Mine (M) ** using Machine learning.

## Dataset
File: 'sonar_data.csv'
208 samples, 61 numeric features (sonar energy at different frequency bands)
Target: 'R' (rock) or 'M' (Mine)

## Approach
Load and explore the data
split into train&test sets
Train a model(Here we used SVM as we have less data and svm performs well with frequencies) 
Evaluate accuracy on test data 

## Results
Training accuracy: 96.99%
Test accuracy: 92.89%

##Installation
git clone https://github.com/premkumarsepuri/Sonar-Signal-Classification.git
Cd Sonar-Signal-Classification
pip install numpy pandas scikit-learn jupter
<img width="1364" height="527" alt="Screenshot 2026-10-26 at 11 47 20 AM" src="https://github.com/user-attachments/assets/1db03d52-2c36-4da8-898e-15a757cac8f6" />
<img width="1357" height="580" alt="Screenshot 2026-10-26 at 11 33 09 AM" src="https://github.com/user-attachments/assets/307a1252-e73e-4742-b930-8629d18a7906" />

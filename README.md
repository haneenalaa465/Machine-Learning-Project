# Project Overview

This project was completed as part of the Machine Learning course at Zewail University in Spring 2024. This project aims to perform activity recognition using the MHEALTH dataset. The dataset is analyzed and classified using various machine learning models, including k-Nearest Neighbors (KNN), Support Vector Machine (SVM), Neural Networks, and Logistic Regression. The primary objective is to identify the best-performing model based on evaluation metrics such as accuracy, precision, recall, and F1-score.

# Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Dataset](#dataset)
- [Models and Evaluation](#models-and-evaluation)
- [Results](#results)
- [Conclusion](#conclusion)
- [Usage](#usage)

# Installation
To run this project, you need to have Python installed along with the following packages:

- numpy
- pandas
- scikit-learn
- tensorflow
- matplotlib

You can install these packages using pip:
```
pip install numpy pandas scikit-learn tensorflow matplotlib
```
# Dataset
The MHEALTH dataset is used for this project. The dataset contains recordings from various sensors placed on different parts of the body to monitor physical activities. The data includes features like acceleration, gyro, and magnetometer readings.

# Models and Evaluation
The following models were implemented and evaluated:

1. k-Nearest Neighbors (KNN)
2. Support Vector Machine (SVM)
3. Neural Network
4. Logistic Regression

# Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
  
# Results
## Model Performance

- **KNN**: Achieved an accuracy of approximately 95%.
- **SVM**: Achieved an accuracy of around 95%.
- **Neural Network**: Achieved an accuracy of approximately 94%.
- **Logistic Regression**: Achieved the lowest accuracy at approximately 54%.
  
## Best-Performing Model
The SVM model with an RBF kernel is identified as the best model for activity recognition on the MHEALTH dataset, achieving the highest accuracy and robust performance in classifying different activities.

# Conclusion
The project concludes that KNN and SVM models are the most effective for activity recognition based on the MHEALTH dataset. Neural Networks also show promising results, while Logistic Regression is less effective due to its inability to capture nonlinear relationships in the data.

# Usage
To run the project, execute the main notebook file (ML_Project_HaneenAlaa_202210463.ipynb). Ensure the dataset is available in the same directory or update the path in the notebook accordingly.

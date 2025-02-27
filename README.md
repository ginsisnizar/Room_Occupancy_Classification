## Room Occupancy Classification
This project focuses on Machine Learning-based Room Occupancy Classification using sensor data. The goal is to predict room occupancy status based on various environmental features such as temperature, humidity, CO2 levels, and light intensity.

## Dataset
The dataset contains sensor readings collected over time, which are used to classify whether a room is occupied or not occupied.
The main file used: Occupancy_Estimation.csv

## Methodology
Data Preprocessing (Handling missing values, feature scaling, SMOTE for class balancing)
Exploratory Data Analysis (EDA) with visualizations
Model Training using various classification algorithms (Decision Tree, Random Forest, SVM, etc.)
Performance Evaluation using accuracy, precision, recall, and confusion matrix

## Files Included
Room_Occupancy_Classification.ipynb → Jupyter Notebook with code implementation
Occupancy_Estimation.csv → Dataset used for model training and testing

## Result
Result
The model evaluation was performed, and different algorithms were compared based on accuracy, precision, recall, and confusion matrix. The accuracy of each model is as follows:

Logistic Regression Accuracy: 99.95%
KNN Accuracy: 99.90%
SVM Model Accuracy: 99.95%
Random Forest Accuracy: 99.95%
Gradient Boosting Model Accuracy: 99.95%
XGBoost Model Accuracy: 99.85%
Although most models achieved very high accuracy, we also analyzed precision, recall, and confusion matrices to determine the most suitable model for deployment.

## Conclusion
Based on the evaluation, Logistic Regression, SVM, Random Forest, and Gradient Boosting all achieved the highest accuracy of 99.95%, making them excellent choices for this classification task.
However, considering real-world applications:
Random Forest and Gradient Boosting are more robust for handling complex data patterns and missing values.
Logistic Regression and SVM are simpler models with high interpretability and lower computational cost.
For practical use, Random Forest or Gradient Boosting is recommended due to their strong generalization, better feature importance analysis, and resilience to noise in sensor data.

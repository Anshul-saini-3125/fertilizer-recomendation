
# Fertilizer Recommendation System Using Machine Learning

## 1. Project Introduction

The Fertilizer Recommendation System is a Machine Learning
based project that predicts suitable fertilizer categories
based on soil nutrients, environmental conditions and crop type.

The system uses a Random Forest Classifier to analyze input
features and recommend a fertilizer category.

## 2. Project Objectives

- To analyze soil nutrient values.
- To identify suitable fertilizer categories.
- To use Machine Learning for fertilizer prediction.
- To improve understanding of smart agriculture.
- To develop an automated fertilizer prediction system.

## 3. Technologies Used

- Python
- Machine Learning
- Random Forest Classifier
- Pandas
- NumPy
- Scikit-learn
- Joblib

## 4. Input Parameters

1. Nitrogen (N)
2. Phosphorus (P)
3. Potassium (K)
4. Temperature
5. Humidity
6. Soil Moisture
7. Soil Type
8. Crop Type

## 5. Fertilizer Categories

The model predicts one of the following categories:

- Urea
- DAP
- MOP
- NPK 10-26-26
- NPK 20-20-0-13
- SSP

## 6. Project Structure

fertilizer_recommendation_ml/
|
|-- fertilizer_dataset.csv
|-- fertilizer_model.joblib
|-- train.py
|-- predict.py
|-- requirements.txt
|-- README.md

## 7. Installation

Install the required Python libraries:

pip install -r requirements.txt

## 8. Model Training

Run the following command:

python train.py

The training script:
- Loads the dataset.
- Preprocesses input features.
- Splits data into training and testing sets.
- Trains a Random Forest classifier.
- Evaluates model performance.
- Saves the trained model.

## 9. Model Prediction

Run:

python predict.py

Enter the required soil and crop information.

The system displays:
- Predicted fertilizer category.
- Model confidence.
- Top three predictions.

## 10. Machine Learning Algorithm

Random Forest Classifier is used for classification.

It combines multiple decision trees to generate
a final prediction.

## 11. Model Performance

Test accuracy obtained in the demonstration:

Approximately 92.92%.

This result is based on a synthetic educational dataset
and does not represent validated agricultural accuracy.

## 12. Future Scope

- Develop a Flask-based web application.
- Add a farmer registration system.
- Integrate weather information.
- Use real-world soil testing datasets.
- Add fertilizer dosage estimation validated by experts.
- Develop a mobile application.

## 13. Conclusion

The project demonstrates the use of Machine Learning
in smart agriculture.

It provides an educational prototype for predicting
fertilizer categories using soil and crop information.

Note: Actual fertilizer selection and dosage must be
based on certified soil testing and local agricultural guidance.

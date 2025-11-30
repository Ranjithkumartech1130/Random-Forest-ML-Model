# Random-Forest-ML-Model
**Heart Disease Prediction – Machine Learning Project**
This project is a simple machine learning model that predicts whether a person has heart disease based on some medical input values. I used the popular Heart Disease dataset and built a Random Forest Classifier to make the predictions.
The main idea of this project is to understand the ML workflow from start to finish loading data, preprocessing, training the model, checking accuracy, and testing it on new inputs.
**What this project does**
Reads the heart dataset
Splits the data into training and testing sets
Normalizes the features using StandardScaler
Trains a Random Forest Classifier
Evaluates the model using accuracy and classification report
Shows which features are most important for prediction
Saves the model and scaler as .pkl files
Allows prediction for a new patient’s data
**Model Used**
I chose Random Forest because:
It gives good accuracy
Works well with mixed types of features
Does not overfit easily
Can show feature importance
Easy to train and understand
The model worked well with this dataset and produced strong accuracy.
**Feature Importance**
I also added a plot that shows which features influenced the model the most.
For example:
Chest pain type (cp)
Maximum heart rate (thalach)
ST depression (oldpeak)
Age
Cholesterol
This gives a clear idea of what the model “looks at” during prediction.
**Ways to run this model**
1)Install Needies    *pip install numpy pandas scikit-learn matplotlib seaborn joblib*
2)Run this Model with google colab with the given dataset
3)Run the code step by step in colab.
I built this mainly to practice supervised machine learning and understand how real-life datasets work. It helped me learn about preprocessing, scaling, model training, evaluation, and visualizations.

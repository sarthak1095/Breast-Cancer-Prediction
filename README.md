# Breast-Cancer-Prediction

Breast Cancer Detection

This project focuses on breast cancer detection using machine learning techniques. The goal is to build models that can accurately classify breast tumors as benign or malignant based on various features.

Dataset

The dataset used for this project is sourced from Kaggle and contains information about breast cancer tumors. The dataset includes features such as radius, texture, perimeter, area, smoothness, compactness, concavity, symmetry, and fractal dimension.

Code

The code is implemented in a Jupyter Notebook file named "Breast Cancer Detection.ipynb". It covers the following steps:

Data preprocessing:

Importing necessary libraries
Loading the dataset
Handling missing data
Encoding categorical variables
Splitting the dataset into train and test sets
Feature scaling
Model building and evaluation:
Logistic regression
Random forest
XGBoost
Randomized search for parameter optimization:
Conducting a randomized search to find the best parameters for logistic regression using cross-validation
Final model:
Training the logistic regression model with optimized parameters
Evaluating the performance of the final model
Results
The project provides the following evaluation metrics for each model:

Accuracy
Precision
Recall
F1 Score
Additionally, cross-validation is performed to estimate the models' performance on unseen data.


Usage

To run the code and reproduce the results, follow these steps:

Clone the repository.
Open the Jupyter Notebook file "Breast Cancer Detection.ipynb" in Jupyter Notebook or any compatible environment.
Ensure the required libraries are installed.
Run the code cells sequentially to execute the data preprocessing steps, model building, and evaluation.
The final results and performance metrics will be displayed in the notebook.
Feel free to explore and modify the code as needed to further analyze the dataset or experiment with different models and techniques.

References

Dataset source: Breast Cancer Wisconsin (Diagnostic) Data Set  

Credits

I would like to give credit to the "Build 10 Real World Machine Learning Projects" by "Vijay Gadhave". The code and project structure in this repository were developed based on the lessons and instructions provided in the course. I highly recommend checking out the course for detailed explanations and in-depth learning.

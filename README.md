# Accident Severity Prediction

This project involves building a supervised machine learning model to predict the severity of accidents, classifying them as fatal or non-fatal. The data is sourced from the Toroo police website, and the project includes data preprocessing, transformation, handling imbalanced classes, numerical encoding, and model evaluation using various algorithms.

## Project Overview

- **Objective:**
  - Predict whether an accident is fatal or non-fatal.

- **Data Source:**
  - Live dataset available from the Toroo police website.

## Workflow

1. **Data Collection:**
   - Retrieved live accident data from the Toroo police website.

2. **Data Preprocessing:**
   - Cleaned and preprocessed the raw data to handle missing values and irrelevant information.

3. **Data Transformation:**
   - Transformed categorical features into numerical encoding suitable for machine learning models.

4. **Handling Imbalanced Classes:**
   - Employed techniques to address imbalanced class distribution in the target variable.

5. **Model Training:**
   - Utilized Pipelines to streamline the data preprocessing and model training processes.
   - Created and trained five different models: XGBoost, SVM, Decision Tree, Random Forest, and Logistic Regression.

6. **Model Evaluation:**
   - Evaluated the performance of each model using appropriate metrics, such as accuracy, precision, recall, and F1-score.
   - Identified the best-performing model for the task.

7. **Visualization and Reporting:**
   - Used PowerBI to visualize and analyze the data, creating comprehensive reports.

8. **Model Serialization:**
   - Stored the trained model in a pickle file, facilitating easy deployment.

9. **Frontend and Deployment:**
   - Created a frontend for user interaction.
   - Developed a Flask web application to deploy the project locally.

## Dependencies

- The project is implemented in Python and relies on the following libraries:
  - scikit-learn
  - xgboost
  - pandas
  - Flask
  - PowerBI

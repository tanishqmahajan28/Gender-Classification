# Gender Classification Project

This project focuses on developing a machine learning model for gender classification. The model predicts an individual's gender based on various features such as age, height, weight, and more. The dataset used for training and evaluation was sourced from Kaggle.

## Table of Contents

- [Overview](#overview)
- [Who Will Find This Helpful](#who-will-find-this-helpful)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature Engineering](#feature-engineering)
- [Models Implemented](#models-implemented)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Conclusion and Future Work](#conclusion-and-future-work)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

Gender classification involves identifying the gender of an individual based on various input features. This project implements several machine learning and deep learning models to perform this classification with high accuracy.

## Who Will Find This Helpful

This project will be particularly helpful for:

- **Data Scientists and Machine Learning Practitioners:** Looking to explore and implement classification models for real-world datasets.
- **Students and Researchers:** Interested in studying gender classification and exploring the impact of feature engineering on model performance.
- **Developers and Engineers:** Working on applications that require gender classification as a component, such as targeted marketing or personalized user experiences.
- **Educators:** Seeking practical examples to demonstrate machine learning concepts in academic settings.

## Dataset

The dataset used for this project was obtained from Kaggle. It includes information about individual's Facial Structure Metrics such as length of hair, height of forehead, node width, node length, distance from nose to lip and other relevant features.

## Data Preprocessing

1. **Data Loading**: The dataset was loaded into the environment and any missing values were handled appropriately.
2. **Data Cleaning**: Incomplete or corrupted data points were removed, and potential biases were addressed by evaluating the data's representativeness.
3. **Data Augmentation**: Synthetic samples were generated to balance the dataset and improve the robustness of the model.
4. **Data Standardization**: Features were scaled to a common range to ensure each contributes equally to the model's performance.

## Exploratory Data Analysis

Visualizations such as histograms, box plots, and scatter plots were used to explore the distribution of features and identify potential relationships within the data. This step provided insights that guided feature selection and model training.

## Feature Engineering

The following feature engineering techniques were applied:

- **Forehead Area:** Calculated by multiplying `forehead_width_cm` and `forehead_height_cm`.
- **Forehead Ratio:** The ratio of `forehead_width_cm` to `forehead_height_cm` to assess proportionality.
- **Nose Area Approximation:** Estimated using width and length features.
- **Nose-to-Lip Ratio:** Ratio of `distance_nose_to_lip_long` to `nose_long` to capture proportionality.
- **Symmetry Index:** Created by comparing features to assess facial symmetry.
- **Interaction Terms:** Combined features like `forehead_width_cm * nose_wide` to capture complex relationships.

## Models Implemented

The project implemented several machine learning and deep learning models, including:

- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Random Forest**
- **Decision Tree**
- **Artificial Neural Network (ANN)**

## Model Evaluation

The models were evaluated based on several metrics:

- **Accuracy**: Overall percentage of correct predictions.
- **Precision**: Fraction of correctly predicted positive cases among all predicted positives.
- **Recall**: Fraction of correctly predicted positive cases among all actual positives.
- **F1 Score**: Harmonic mean of precision and recall.
- **Confusion Matrix**: A table showing actual vs. predicted classifications.

## Results

- **Best Performing Model**: Random Forest, with a test accuracy of 96.4%.
- **Comparison**: All models performed well, with minor differences in accuracy and precision.

## Conclusion and Future Work

The project successfully developed a gender classification system with high accuracy.

## Contact

For any queries or suggestions, please contact Tanishq Mahajan at trmahajan28@gmail.com.

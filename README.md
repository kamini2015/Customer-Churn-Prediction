# Customer Churn Prediction Project

This project aims to predict customer churn using an artificial neural network (ANN) model. The dataset used for this project is the Telco Customer Churn dataset obtained from Kaggle.

## Dataset Description

The Telco Customer Churn dataset contains information about customers of a telecommunications company, including demographic information, services subscribed to, and churn status.

## Code Overview

The project is implemented in Python using Google Colaboratory. Here's a brief overview of the code:

1. **Data Loading**: The dataset is loaded from a zip file obtained from a specified URL. It is then extracted and loaded into a Pandas DataFrame.

2. **Data Preprocessing**: Data preprocessing steps include handling missing values, converting categorical variables into numerical format, and scaling numerical features.

3. **Exploratory Data Analysis (EDA)**: EDA is performed to gain insights into the dataset, visualize distributions, and understand the relationships between variables.

4. **Model Building**: An ANN model is built using TensorFlow and Keras. The model architecture consists of input, hidden, and output layers. The model is compiled with appropriate loss function and metrics and trained on the training data.

5. **Model Evaluation**: The trained model is evaluated on the test data using various performance metrics such as accuracy, precision, recall, and F1-score.

6. **Visualization**: Confusion matrix and classification report are visualized to assess the performance of the model.

## How to Use

To run the code:

1. Open the provided Google Colaboratory link.
2. Execute each code cell sequentially.
3. Make sure to have necessary libraries installed. If not, install them using pip.
4. Follow the instructions provided in the comments to understand each step of the code.

## Requirements

The code requires the following Python libraries:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- TensorFlow

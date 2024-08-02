# Credit Score Prediction

This project provides a machine learning model to predict credit scores based on various financial features. It uses a dataset of financial attributes and credit scores to train a model, evaluates its performance, and allows for interactive predictions.

## Project Structure

- `cs.csv`: Dataset containing financial attributes and credit scores.
- `credit_score_prediction.py`: Python script for training the model, evaluating performance, and making predictions.
- `README.md`: This file.

## Requirements

Ensure you have the following libraries installed:

- `pandas`
- `numpy`
- `scikit-learn`
- `plotly`

You can install the required libraries using `pip`:

```bash
pip install pandas numpy scikit-learn plotly

How to Use

Load and Prepare Data:
The dataset cs.csv is loaded and preprocessed.
Categorical values in the Credit_Score column are encoded to numerical labels.
Features are scaled using StandardScaler.
Train and Evaluate the Model:
A RandomForestClassifier is used as the example model. You can replace it with any other model of your choice.
The data is split into training and testing sets.
Model performance is evaluated using accuracy, confusion matrix, and classification report.
Interactive Prediction:
The script allows for interactive input from the user to predict credit scores based on new data.
Visualization:
A box plot is created to visualize credit scores based on annual income.

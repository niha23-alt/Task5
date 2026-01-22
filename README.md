# Task 5: Train-Test Split & Evaluation Metrics

## Objective
The objective of this task is to understand the importance of splitting data into training and testing sets
and to evaluate a machine learning model using standard evaluation metrics.

## Dataset
Heart Disease Dataset  
Source: https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

## Tools & Technologies
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook

## Steps Performed
- Loaded the Heart Disease dataset
- Separated features and target variable
- Split the dataset into training and testing sets
- Trained a Logistic Regression model
- Predicted results on test data
- Evaluated the model using accuracy, precision, recall, and confusion matrix

## Model Used
Logistic Regression

## Evaluation Metrics
- **Accuracy**: Measures the overall correctness of the model
- **Precision**: Indicates how many predicted positive cases were actually positive
- **Recall**: Measures how many actual positive cases were correctly identified
- **Confusion Matrix**: Displays true positives, true negatives, false positives, and false negatives

## Evaluation Report
The Logistic Regression model was evaluated on the test dataset using standard performance metrics.
The accuracy score indicates that the model predicts the presence of heart disease effectively.

Precision shows that most of the predicted heart disease cases were correct, while recall confirms
that the model successfully identified the majority of actual heart disease cases.

The confusion matrix provided a detailed breakdown of correct and incorrect predictions,
helping in understanding the model's classification performance.

Overall, the model demonstrated good generalization ability on unseen data without signs of overfitting.

## Conclusion
This task helped in understanding the importance of model evaluation and interpreting
machine learning performance metrics using real-world data.

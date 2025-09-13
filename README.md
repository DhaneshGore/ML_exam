# Sentiment Analysis with Logistic Regression & MLflow

This project implements a sentiment analysis model using Logistic Regression on a large Twitter dataset.
We use TF-IDF for feature extraction, track experiments with MLflow, and save the trained model as .pkl for reuse and deployment.

## 📌 Features
- Preprocess raw text (tokenization, stopword removal, lemmatization)  
- Generate features using **TF-IDF Vectorizer**  
- Train a **Logistic Regression** classifier  
- Perform **hyperparameter tuning** with GridSearchCV  
- Track experiments (parameters, metrics, models) using **MLflow**  
- Save the best model as `.pkl` and log it in MLflow  


# 📊 Experiment Results (MLflow)

One of the tracked runs achieved the following results using Logistic Regression with hyperparameters:

## Parameters

algorithm: Logistic Regression
C: 0.1
max_iter: 1000
solver: liblinear

### Metrics

#### Accuracy: 0.80
#### Precision: 0.85
#### Recall: 0.83
#### F1 Score: 0.84

These metrics were logged and visualized in MLflow for easy comparison with other runs.


# MLflow

![image](https://github.com/user-attachments/assets/e7e2ad5c-68fe-49f9-be66-4e7974d1a537)


#application 

![image](https://github.com/user-attachments/assets/706a9fb6-c5ab-4fc2-ae73-1365fcb1f9d7)

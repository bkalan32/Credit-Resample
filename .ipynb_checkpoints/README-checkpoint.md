# Credit Risk Classification
This repository contains code and analysis for a credit risk classification project. The goal of this project is to build machine learning models that can identify the creditworthiness of borrowers using historical lending activity data.

Overview
Credit risk poses a classification problem that’s inherently imbalanced, as healthy loans easily outnumber risky loans. In this project, we address this challenge by using various techniques to train and evaluate models with imbalanced classes. We utilize a dataset of lending activity from a peer-to-peer lending services company to develop a model that can predict the creditworthiness of borrowers.

Subsections
The project is organized into the following subsections:

Split the Data into Training and Testing Sets: In this step, we split the dataset into training and testing sets, preparing the data for model training and evaluation.

Create a Logistic Regression Model with the Original Data: We fit a logistic regression model using the original data and evaluate its performance by calculating accuracy, generating a confusion matrix, and printing a classification report.

Predict a Logistic Regression Model with Resampled Training Data: To address the imbalanced classes, we resample the training data using RandomOverSampler and fit another logistic regression model. We evaluate its performance using accuracy, confusion matrix, and classification report.

Credit Risk Analysis Report: Finally, we provide a summary and analysis of the performance of both machine learning models used in this project, along with our recommendation for model selection.

Results
Logistic Regression Model with Original Data
Accuracy Score: [Insert Accuracy Score]
Confusion Matrix: [Insert Confusion Matrix]
Classification Report: [Insert Classification Report]
Logistic Regression Model with Resampled Data
Accuracy Score: [Insert Accuracy Score]
Confusion Matrix: [Insert Confusion Matrix]
Classification Report: [Insert Classification Report]
Summary
In this project, we built and evaluated two logistic regression models for credit risk classification: one using the original data and another using resampled data.

The logistic regression model trained on the original data achieved an accuracy score of [Insert Accuracy Score]. However, the model had challenges in predicting the minority class (high-risk loans) due to the imbalanced nature of the dataset.

To address the class imbalance, we resampled the training data using RandomOverSampler, creating an equal number of data points for each label. The logistic regression model trained on the resampled data achieved an accuracy score of [Insert Accuracy Score]. This model showed improved performance in predicting both the majority and minority classes.

Based on our analysis, we recommend using the logistic regression model trained on the resampled data for credit risk classification. This model demonstrates better overall performance, including improved accuracy and balanced prediction of both healthy and high-risk loans.

It's important to note that credit risk classification is a complex task, and there may be other advanced techniques or models worth exploring. Further experimentation and evaluation are encouraged to refine the credit risk classification process and potentially achieve even better results.

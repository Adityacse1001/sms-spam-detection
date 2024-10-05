# SMS Spam detection

# Overview
SMS Spam Detection is a machine learning model that takes an SMS as input and predicts whether the message is a spam or not spam message. The model is built using Python and deployed on the web using Streamlit.

# Datasets
Datasets for the project was collected from - https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

# Key Features
### 1. Datasets collection
The SMS Spam Detection project begins with data collection, where a labeled dataset of SMS messages is gathered

### 2. Data Cleaning and Preprocessing 
The next step involves data cleaning and preprocessing, which includes handling missing values, normalizing text by converting to lowercase, removing special characters, stopwords, and performing tokenization and feature extractio

### 3. Exploratory Data Analysis (EDA)
exploratory data analysis (EDA) is conducted to gain insights into the data, visualize distributions, and analyze patterns. This helps in understanding the underlying structure of the dataset.

### 4. Model Building and Selection
In the model building and selection phase, various machine learning models, such as Extra Trees Classifier and Voting Classifier, are trained and evaluated using accuracy, precision, recall, and F1-score metrics. Cross-validation is used to select the model with the best performance.

## Results

The trained model achieved an **accuracy of 97.10 %** and **Precision is 100 %** on the test set and performed well in terms of precision, recall, and F1-score.

| Metric     | Score |
|------------|-------|
| Accuracy   | 97.10 %   |
| Precision | 100 %   |
| Recall     | 76.19 %   |
| F1-score   | 86.49 %   |

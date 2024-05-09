# Text-Classification-Spam-Email

This project focuses on the "Spam or Not Spam Dataset," which is a collection of emails labeled as either spam or not spam. The dataset can be accessed and downloaded from the following Kaggle URL: [Spam or Not Spam Dataset.](https://www.kaggle.com/ozlerhakan/spam-or-not-spam-dataset)

# Objective
The objective of this project is to train and evaluate machine learning models in the field of email spam classification. By developing a model that can accurately classify incoming emails as either spam or not spam, the project aims to create a robust solution for filtering out unwanted and potentially harmful messages.

# Workflow

1. Text Conversion Data Preprocessing:
   
It aims to convert raw text data into a format that can be used for machine learning tasks:

Data Acquisition: Obtain the raw text data from a suitable source, such as a dataset or text documents.
Text Cleaning: Perform data cleaning operations to remove any irrelevant or noisy information from the text data. This may involve tasks like removing special characters, punctuation, or HTML tags.
Tokenization: Split the text into individual tokens, such as words or n-grams, to create a tokenized representation of the text data.

2. Classification

It aims to perform classification tasks on the preprocessed text data:

Data Split: Split the preprocessed text data into training and testing sets to evaluate the performance of the classification model.
Model Selection: Choose a suitable classification algorithm, which is MultinomialNB() for discrete frequency features, based on the nature of the problem and available resources.
Model Training: Train the selected classification model using the training set of preprocessed text data.
Model Evaluation: Evaluate the trained model's performance using appropriate evaluation metrics, such as precision_score, recall_score, f1_score, on the testing set.

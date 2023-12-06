# My-Portfolio
This repository contains the files of my personal portfolio website and 3 blog posts.

### Blog Post 1: Titanic - Machine Learning from Disaster

In this blog post, We will try predicting survival on the Titanic using a logistic regression model.

### Blog Post 2: Leveraging TensorFlow and TPU for Image Classification: Petals to the Metal - Flower Classification on TPU

This blog post goes into a real-world example, showing how to use TensorFlow and TPUs (Tensor Processing Units) to solve 'Petals to the Metal - Flower Classification on TPU'

### Blog Post 3: Building a Naive Bayes Classifier to Identify AI-Generated Text

The goal of this blog post is to explain how to build a classifier that can predict whether an essay was written by a human or generated by a Large Language Model (LLM). The classifier is trained on a dataset consisting of essays, some written by students and others generated by various LLMs.

Key Features:
1) NLTK for Text Processing: Tokenization, lemmatization, and removal of stopwords and punctuation.
2) Custom Vocabulary Building: Creation of a vocabulary list, omitting rare words.
3) Vectorization of Text: Conversion of tokenized text to a numerical format using CountVectorizer.
4) Naive Bayes Classification: Implementation of the Naive Bayes algorithm for text classification.
5) Visualization: Use of Matplotlib to visualize the top predictive words for each class.
6) Performance Evaluation: Evaluation of the model's accuracy and performance on a test dataset.

How to Run the Project

Set Up Your Environment:
Ensure Python 3.x is installed on your system.
Install necessary Python libraries: pandas, numpy, nltk, scikit-learn, matplotlib.

Download the Dataset:
Place the dataset in a directory accessible to the script. Update the file path in the script accordingly. Dataset link: https://www.kaggle.com/competitions/llm-detect-ai-generated-text/data

Running the Script:
Execute the Python script attached in the blog post. It will perform the data processing, model training, evaluation, and visualization steps.

Viewing the Results:
The script will output a classification report and visualizations of the top predictive words.
The final predictions are saved in a CSV file, ready for submission if applicable.

Dependencies:
Python 3.x,
Pandas,
NumPy,
NLTK,
Scikit-learn,
Matplotlib.

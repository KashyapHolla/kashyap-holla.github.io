# My-Portfolio
This repository contains the files of my personal portfolio website and 3 blog posts.

### Blog Post 1: Titanic - Machine Learning from Disaster

In this blog post, We will try predicting survival on the Titanic using a logistic regression model.

Key Features:
1) Data Preprocessing: The project includes cleaning and preparing the dataset, handling missing values, and converting categorical variables into a format suitable for modeling.
2) Feature Engineering: Important features are extracted and transformed to improve model performance.
3) Logistic Regression Model: Utilizes a logistic regression model to predict survival, a classical binary classification problem.
4) Model Pipeline: Implements a pipeline with data standardization and logistic regression for effective modeling.
5) Prediction and Output: Generates predictions for the test dataset and saves the output in the correct submission format.

How to Run the Project

Set Up Your Environment:
Ensure Python 3.x is installed on your system.
Install necessary Python libraries: pandas, numpy, matplotlib, scikit-learn.

Download the Dataset:
The dataset can be found on the Titanic Kaggle competition page.
Place the dataset in a directory accessible to the script.
Dataset link: https://www.kaggle.com/competitions/titanic/data

Running the Script:
Execute the Python script named as titanic.ipynb. It will perform data preprocessing, model training, and generate predictions.

Viewing the Results:
The script outputs a CSV file with the predicted survival of passengers in the test dataset.

Dependencies
Python 3.x,
Pandas,
NumPy,
Matplotlib,
Scikit-learn.

### Blog Post 2: Leveraging TensorFlow and TPU for Image Classification: Petals to the Metal - Flower Classification on TPU

This blog post goes into a real-world example, showing how to use TensorFlow and TPUs (Tensor Processing Units) to solve 'Petals to the Metal - Flower Classification on TPU'.

Key Features
1) TensorFlow 2.x and TPU Integration: Leverages the speed and efficiency of TPUs provided by TensorFlow for high-performance model training.
2) Data Preprocessing and Augmentation: Implements data loading, preprocessing, and augmentation techniques suitable for image data.
3) VGG16 Pretrained Model: Utilizes VGG16, a pre-trained convolutional neural network model for image classification.
4) Custom Training Loop: Configures a custom training and validation loop, including a learning rate scheduler.
5) Performance Metrics: Evaluates the model using F1 score, precision, recall, and confusion matrix.
6) Prediction and Submission: Generates predictions for a test dataset and prepares a submission file.

How to Run the Project
Set Up Your Environment:
Ensure you have TensorFlow 2.x installed.
Run the script in an environment with TPU support, like Google Colab or Kaggle Kernels.

Download the Dataset:
Dataset link: [https://www.kaggle.com/competitions/titanic/data](https://www.kaggle.com/competitions/tpu-getting-started/data)

Running the Script:
Execute the Python script named as Kashyap_Holla_Flower_Classification.ipynb. It will perform dataset loading, model building, training, and evaluation.
The script prints out the training process and evaluation metrics.

Viewing the Results:
The script will display training curves, confusion matrices, and example predictions.
A CSV file with predictions for the test dataset (submission.csv) will be generated.

Dependencies
TensorFlow 2.x,
NumPy,
Matplotlib,
Python 3.x.

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
Execute the Python script attached in the blog post and also present inside the Data folder as text_classifier.ipynb. It will perform the data processing, model training, evaluation, and visualization steps.

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

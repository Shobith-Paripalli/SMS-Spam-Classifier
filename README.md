# SMS Spam Classifier

## Overview

This project is an SMS Spam Classifier that identifies whether a given message is spam or ham (not spam). It is built using the Naive Bayes algorithm, which achieves an accuracy of 98%. The project includes various stages such as data preprocessing, visualization, and model building. Additionally, a user-friendly GUI is created using Tkinter, allowing users to input a message and instantly get a classification result.

## Features

- **Naive Bayes Model:** 
  - The model is trained using the Naive Bayes algorithm, known for its efficiency in text classification tasks.
  - Achieves an accuracy of 98% on the test dataset.

- **Data Preprocessing:**
  - Includes text cleaning and tokenization.

- **Visualization:**
  - Provides insights into the dataset with visualizations such as word clouds, frequency distributions, etc.
  
- **Interactive GUI:**
  - A Tkinter-based graphical user interface allows users to type in a message and determine if it is spam or ham.
  
## Dataset

The model is trained on a publicly available SMS spam dataset in Kaggle, which consists of labeled messages as either spam or ham. Preprocessing steps have been applied to clean and prepare the data for modeling.

## Results

- **Accuracy:** 98% 
- **Precision:** 99% for ham, 97% for spam 
- **Recall:** 100% for ham, 91% for spam
- **F1-Score:** 99% for ham, 94% for spam


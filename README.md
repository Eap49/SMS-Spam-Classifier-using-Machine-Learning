
# SMS Spam Classifier using Machine Learning

## Overview

This project aims to automatically classify SMS messages as spam or ham (not spam) using machine learning and natural language processing (NLP). It uses the SMSSpamCollection dataset, which contains labeled SMS messages. The workflow includes data cleaning, text preprocessing, feature extraction (TF-IDF), and training two models: Naive Bayes and Support Vector Classifier (SVC). The project also addresses class imbalance using SMOTE and evaluates model performance with cross-validation and multiple metrics.

## Features

- Cleans and preprocesses SMS text (lowercasing, removing stopwords, stemming)
- Converts text to numerical features using TF-IDF
- Handles class imbalance with SMOTE
- Trains and evaluates Naive Bayes and SVC models
- Provides classification metrics and visualizations
- Includes a function to predict new messages as spam or ham

## How to Use

1. Clone the repository:
    ```
    git clone https://github.com/yourusername/sms-spam-classifier.git
    cd sms-spam-classifier
    ```
2. Install the required libraries:
    ```
    pip install numpy pandas scikit-learn imbalanced-learn nltk matplotlib seaborn beautifulsoup4 lxml
    ```
3. Download the [SMSSpamCollection dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection) and place it in the project folder.
4. Run the main script or Jupyter Notebook to train and evaluate the models.
5. Use the `predict_message()` function to classify new SMS messages.

## Results

- Naive Bayes and SVC both achieve high accuracy.
- Naive Bayes generally provides more stable results across test sets.
- The classifier can be used for real-world SMS spam filtering applications.

## License

This project is for educational purposes.

---

*Feel free to contribute or suggest improvements!*

# Spam Email Classifier

A **machine learning-based spam email classifier** built using Python, Scikit-Learn, and Natural Language Processing (NLP) techniques. This project preprocesses email text, converts it to numerical features using TF-IDF (with bigrams), handles class imbalance with SMOTE, and trains a Logistic Regression model to predict whether an email is **Spam** or **Not Spam**.

## Features

- **Text Preprocessing:** Uses NLTK for stopword removal and lemmatization.
- **Feature Extraction:** Converts text data into numerical features using TF-IDF vectorization.
- **Imbalanced Data Handling:** Utilizes SMOTE to balance the dataset.
- **Classification:** Employs Logistic Regression to classify emails.
- **Interactive Prediction:** Accepts user input to classify custom email messages.

## Tech Stack

- **Python 3.12 can be your latest version of your time**
- **Pandas & NumPy:** For data handling and numerical operations.
- **NLTK:** For natural language processing (stopword removal & lemmatization).
- **Scikit-Learn:** For TF-IDF vectorization, model training, and evaluation.
- **Imbalanced-learn (SMOTE):** For handling imbalanced datasets.

## Installation Guide

### Clone the Repository
```sh
git clone https://github.com/Abhishek-Verma0/Spam-Email-Classifier.git
cd Spam-Email-Classifier

```
# Contributing to Spam Email Classifier

We welcome contributions! Follow the steps below to contribute effectively.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/NewFeature`)
3. Commit changes (`git commit -m 'Add NewFeature'`)
4. Push to branch (`git push origin feature/NewFeature`)
5. Open a Pull Request
6. Wait for Pull Request get Verified.




## How to predict spam or not spam for given mail

    After cloning repo run " Spam_Email_Classifer.ipynb "
    You can run on google colab  
    When you run it on colab it will ask for email enter the mail text and get prediction 



### Planning  to make an User Interface for this you can also contribute....!
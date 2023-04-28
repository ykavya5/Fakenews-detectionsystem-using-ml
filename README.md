
# Fake News Detection System

This Python code is a machine learning-based system for detecting fake news. It uses the following libraries: 

- pandas
- numpy
- sklearn

## Installation

To run this code, you will need to install the following dependencies:

- Python 3.5+
- pandas
- numpy
- scikit-learn

You can install these dependencies using pip. Here's how:

```
pip install pandas
pip install numpy
pip install scikit-learn
```

## Usage

To use this system, you will need to provide it with a dataset of news articles and their labels (fake or real). You can then use the system to train a machine learning model on the data, and use the model to predict the labels of new articles.

Here's how to use the code:

1. Load the dataset into a Pandas dataframe using the `pd.read_csv()` function.
2. Preprocess the data by removing any unwanted characters, converting text to lowercase, and splitting the data into training and testing sets using the `train_test_split()` function.
3. Train a machine learning model on the training data using the `fit()` function.
4. Use the model to predict the labels of the test data using the `predict()` function.
5. Evaluate the accuracy of the model using the `accuracy_score()` and `classification_report()` functions.

## Data

To train and test the machine learning model, you will need a dataset of news articles labeled as fake or real. The dataset should be in CSV format, with one row per article and two columns: "text" and "label". The "text" column should contain the text of the article, and the "label" column should contain either "fake" or "real".

## Models

This code uses the scikit-learn library to implement the machine learning model. The model used in this code is a Random Forest Classifier.

## Evaluation

To evaluate the performance of the machine learning model, this code uses the accuracy score and classification report. The accuracy score measures the proportion of correct predictions, while the classification report provides a detailed breakdown of the model's performance on each class.

## Contributing

If you would like to contribute to this project, feel free to fork the repository and submit a pull request. We welcome contributions from anyone!


## Contact

If you have any questions or comments about this code, please contact at yamsanikavya15@gmail.com 

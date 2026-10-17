# Movie Hit/Flop Prediction Using Naive Bayes

## Overview
A machine learning project that predicts movie Hit/Flop labels from review text using Natural Language Processing (NLP) and the Multinomial Naive Bayes algorithm.

## Technologies
- Python
- Pandas
- Scikit-learn
- NLP
- CountVectorizer
- Multinomial Naive Bayes
- Joblib

## Workflow
1. Load and inspect the movie review dataset.
2. Encode Hit/Flop target labels using LabelEncoder.
3. Split the dataset into training and testing sets.
4. Convert review text into numerical features using CountVectorizer.
5. Train a Multinomial Naive Bayes classifier.
6. Evaluate predictions using accuracy and a confusion matrix.
7. Save and reload the trained model using Joblib.

## Dataset
The dataset contains movie review text and corresponding Hit/Flop labels.

## Model Evaluation
The model achieved 100% accuracy on the current 38-sample test set. Further testing on independent data is needed to assess real-world performance.

## How to Run
1. Clone or download this repository.
2. Install the required libraries:
   `pip install pandas scikit-learn joblib`
3. Open the notebook in Jupyter Notebook.
4. Run the cells in sequence.

## Author
Alfaiz Khan

# About
Evaluate the predictive performance of different models on multi-label text comments.

# Problem Definition
You are a AI vtuber who need to select the approciate comment to read. However, many of them are toxic and you need to justify which to read

# Introduction

In this project, we will analyze a dataset containing comments that may be toxic. Our goal is to train a model that can effectively predict whether a comment is harmful. We will be using the sklearn library to preprocess the dataset, create features, train the model, and evaluate the performance. We will compare the performance of different models for both multi-label prediction and single-label prediction.

# [Dataset](https://www.kaggle.com/datasets/fizzbuzz/cleaned-toxic-comments)

The dataset we are using is `train_preprocessed.csv`, which consists of comments and their respective labels. These labels include 'identity_hate', 'insult', 'obscene', 'severe_toxic', 'threat', and 'toxic'. Each comment is annotated with binary values for each label, indicating whether the comment is considered toxic under that category.

# Preprocessing and Feature Extraction

We will be using the `CountVectorizer` class from the sklearn library to convert the comments into a matrix of token counts. This representation will serve as the input features for our model. The labels will remain unchan

# Model Training

We will be using the `OneVsRestClassifier` from the sklearn library with `LogisticRegression` as the base classifier. This approach enables the model to predict multiple labels for each comment.

# Conclusion

Utilizing a limited training set comprising merely 150,000 data instances, our model has successfully demonstrated a predictive accuracy exceeding 90%.

# To do list
Testing more model for better performence 

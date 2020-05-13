# Mushroom Classification using Naive Bayes
## Introduction:
On a pizza or in a risotto, mushrooms simply taste great! But with over 10 000 species of mushrooms only in North America, how can we tell which are edible?
This is the objective of this project. We will build a classifier that will determine to which class a certain mushroom belongs to.

![](https://images.fineartamerica.com/images/artworkimages/mediumlarge/1/beautiful-mushrooms-pixabay.jpg)

## Problem Statement:
This is the objective of this project. We will build a classifier that will determine to which class a certain mushroom belongs to.

## Requirements:
- Jupyter Notebook

## Mushrooms Dataset:
The data set we will be using contains 8124 instances of mushrooms with 22 features. Among them, we find the mushroom’s cap shape, cap color, gill color, veil type, etc. Of course, it also tells us if the mushroom is edible or poisonous.

![](https://miro.medium.com/max/1148/1*R5SXza_EHASdxcWEsSrV_Q.jpeg)

## Importing the Modules:
- Numpy
- Pandas
- SkLearn

## Naive Bayes Classifier:
A Naive Bayes classifier is a probabilistic machine learning model that’s used for classification task. The crux of the classifier is based on the Bayes theorem.

**Bayes Theorem:**

![](https://miro.medium.com/max/1020/1*tjcmj9cDQ-rHXAtxCu5bRQ.png)

Using Bayes theorem, we can find the probability of A happening, given that B has occurred. Here, B is the evidence and A is the hypothesis. The assumption made here is that the predictors/features are independent. That is presence of one particular feature does not affect the other. Hence it is called naive.

![](https://miro.medium.com/max/6190/1*39U1Ln3tSdFqsfQy6ndxOA.png)

## Score:
For this model, the accuracy on the test set is **0.998**, which means the model made the right prediction for **99.8%** of the mushrooms in the given dataset. We can expect the model to be correct **99.8%** of the time for predicting the species of mushrooms.

## Summary:
The Mushroom classification problem (and our implementation) is a perfect example to illustrate how a machine learning problem should be approached and how useful the outcome can be to a potential user.

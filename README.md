# Identify and classify toxic online comments
[Toxic Comment Classification Challenge](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data) from kaggle create a model which predicts a probability of each type of toxicity for each comment with a large number of Wikipedia comments which have been labeled by human raters for toxic behavior (toxic , severe_toxic ,obscene , threat , insult ,identity_hate ) 

<p align="center">
  <img width="900" height="500" src="https://storage.googleapis.com/kaggle-media/competitions/jigsaw/003-avatar.png">
</p>

## Overview

### 1) Import Data

### 2) Tokenize Texts

### 3) Convert texts to sequences

### 4) Pad sequences into same size

### 5) Same sizing sequences

### 6) Deploy Embedding layer and LSTM 

### 7) Testing model 

## Performance

<p align="left">
  <img width="480" height="250" src="acc.png">
</p>

<p align="left">
  <img width="480" height="250" src="loss.png">
</p>

***loss: 0.0458 - accuracy: 0.9833 - val_loss: 0.0475 - val_accuracy: 0.9929***

## Purpose of the Project

This model helps social networks and online platforms, both websites and applications, to quickly identify and remove toxic comments and messages and reduce the difficulty of this process

## Technology Stack

* [Tensorflow 2.x](https://www.tensorflow.org/)
* [pandas](https://pandas.pydata.org/pandas-docs/stable/index.html#)
* [numpy](https://numpy.org/)
* [matplotlib](https://matplotlib.org/)

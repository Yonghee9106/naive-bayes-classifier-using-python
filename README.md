# Naïve Bayes Classifier from Scratch in Python
This repository implements a Naive Bayes classifier in Python. It implements the code with Pandas library for data processing, but the Naive Bayes algorithm implemented from scratch without using off-the-shelf machine learning library.

The dataset contains students personal information. Based on dataset, I will train the NB model and predict the grades of students.

# Dataset
For this project, I have adapted the [student.csv](data/student.csv) data set available from the UCI machine learning repository.

* 649 instances
* 30 attributes
* 6 classes, corresponding to predicted final grade: {A+, A, B, C, D, F}
* [student.txt](data/students.txt) explains the attributes and class-labels

Source: https://archive.ics.uci.edu/ml/index.php

# Implementation
**Step 1**
* open a data file in csv, and transform it into a usable format
* use pandas libaray
* get familiar with data attributes

**Step 2**
* split a data set into a training set and hold-out test set
* set the hold-out size

**Step 3**
* build a supervised NB model from training data set

**Step 4**
* predict the class for test data set, based on a trained model

**Step 5**
* evaluate a set of predictions in terms of accuracy

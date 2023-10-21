# Multi-class-classifiers
This repository contains the from-scratch implementations of both multi-class linear SVM and Logistic Regression models and comparisons with their pre-built correspondings.

---
### Project Overview

This notebook contains two from-scratch implemented multi-class classifier models which trained and tested on both an artificial dataset and **DIGITS** dataset. In addition to the from-scratch implemented classifiers, I also used the most similar classifiers implemented by the `sklearn` library to compare the results of both sides. Every classifier used in this notebook, whether it's implemented from-scratch or implemented by `sklearn` library is using **linear** models as it's hypothesis. One of the two from-scratch implementations is using the **multi-class hinge loss** as it's loss function (as the multi-class Support Vector Machine (SVM) method does), and the other is using the **cross-entopy or softmax** as it's loss function (as the multi-class Logistic Regression method does).

So if we want to picture an overview of what have been done in this notebook, it's possible to divide it into the following parts:
 * Implement the from-scratch Support Vector Machine (SVM) classifier.
 * Implement the from-scratch Logistic Regression classifier.
 * Train the both from-scratch SVM and Logistic Regressison models on an artificially created dataset, then test and compare the results and accuracies.
 * Train the both sklearn SVM and Logistic Regresison models on the artificially created dataset, then test and compare the results and accuracies.
 * Train the both from-scratch SVM and Logistic Regressison models on an **DIGITS** dataset, then test and compare the results and accuracies.
 * Train the both sklearn SVM and Logistic Regresison models on the **DIGITS** dataset, then test and compare the results and accuracies.
    

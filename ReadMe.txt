# Predicting drug activity detection

## Introduction

The objective is to build a predictive model to predict given a specific compud is active or not. This is calssic problem of classification. Drugs are typically small organic molecules that achieve their desired activity by binding to a target site on a receptor. The first step in the discovery of a new drug is usually to identify and isolate the receptor to which it should bind, followed by testing many small molecules for their ability to bind to the target site. This leaves researchers with the task of determining what separates the active (binding) compounds from the inactive (non-binding) ones. Such a determination can then be used in the design of new compounds that not only bind, but also have all the other properties required for a drug (solubility, oral absorption, lack of side effects, appropriate duration of action, toxicity, etc.). 
So for this task, a binary classification model is created.


## Dataset
Training set is a sparse binary matrix, patterns in lines, features in columns, with class label 1 or 0 in the first column.


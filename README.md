# Shopping
It builds a k‑nearest‑neighbor classifier to predict whether an online shopping user session will result in a purchase, based on browsing behavior and session data.
Problem overview

When users browse an e‑commerce site, many leave without purchasing.
The goal is to predict purchase intent from session data—like page visits, bounce rates, time spent, month, browser, etc.—so a site could, for example, personalize offers for likely non‑buyers.

Rather than only using overall accuracy, this project emphasizes two metrics:

Sensitivity — true positive rate: proportion of actual buyers correctly predicted.

Specificity — true negative rate: proportion of non‑buyers correctly predicted.

These metrics give a fuller picture than accuracy alone, especially when classes are imbalanced. The project specification from CS50 spells out this approach. 
▶️ How to run

Make sure you have Python and scikit-learn installed.

pip install scikit-learn


Run the program on the dataset:

python shopping.py shopping.csv


You should see output showing correct/incorrect predictions and the true positive and true negative rates, similar to what CS50 describes for the project.

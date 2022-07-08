When I first came across Confusion Matrix, as the name describes it was very confusing. But as I went deeper into it, I realized that the Confusion Matrix actually helps us to summarize the confusion created by the model which makes incorrect predictions.

Difficult to understand? Don’t worry, we will go through the confusion matrix and try to understand it better.

# What is Confusion Matrix?
In short, a confusion matrix is a technique used for summarizing the performance of a classification algorithm i.e. it has binary outputs.

Example for a classification algorithm: Predicting if the patient has cancer. Here, there can only be two outputs i.e. Yes or No.

A confusion matrix gives us a better idea of what our classification model is predicting right and what types of errors it is making.

The number of correct and incorrect predicted values is summarized with count values and stored in the table against the actual values as shown below:

![](https://miro.medium.com/max/974/0*-GAP6jhtJvt7Bqiv.png)

The confusion matrix is very simple to understand, but the related terminology can be confusing.

## Confusion Matrix Terminologies
There are four important terms which define the confusion matrix. We will go through all the terms with a simple example.

```
There are a group of people waiting to examine if they have swine flu. The doctor goes through all the cases and tells the patient if they have the flu or no.
```
Cases in which the doctor predicted YES (they have the disease), and they do have the disease will be termed as **TRUE POSITIVES (TP)**. The doctor has correctly predicted that the patient has the disease.

Cases in which the doctor predicted NO (they do not have the disease), and they don’t have the disease will be termed as **TRUE NEGATIVES (TN)**. The doctor has correctly predicted that the patient does not have the disease.

Cases in which the doctor predicted YES, and they do not have the disease will be termed as **FALSE POSITIVES (FP)**. Also known as *“Type I error”*.

Cases in which the doctor predicted NO, and they have the disease will be termed as **FALSE NEGATIVES (FN)**. Also known as *“Type II error”*.


## Where to place the terms in the Confusion Matrix?

![](https://miro.medium.com/max/1400/0*9r99oJ2PTRi4gYF_.jpg)

Here the idea is to always keep the Predicted (Positive and Negative) values as the rows of the table and the Actual (Positive and Negative) values as the columns of the table. As we see from the table above:

When the Predicted is Positive and the Actual is Positive it is True Positive.

When the Predicted is Negative and the Actual is Negative it is True Negative.

When the Predicted is Positive and the Actual is Negative it is False Positive. As the model has predicted it Positive and it is incorrect so it is False Positive.

When the Predicted is Negative and the Actual is Positive it is False Negative. As the model has predicted it Negative and it is incorrect so it is False Negative.

## Why is Confusion Matrix Important?
Below, are the list of few but important metrics that are computed from a Confusion Matrix for a binary classifier. In simple words, these metrics determine how well the model performs.

* Accuracy
* Precision
* Recall
* F Score
* ROC Curve

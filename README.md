# MLoB
This is the repository of the Masters course Machine Learning in Practice.

## Challenge
You are provided with a large number of Wikipedia comments which have been labeled by human raters for toxic behavior. The types of toxicity are:

* `toxic`
* `severe_toxic`
* `obscene`
* `threat`
* `insult`
* `identity_hate`

You must create a model which predicts a probability of each type of toxicity for each comment.

## File descriptions
* _train.csv_ - the training set, contains comments with their binary labels
* _test.csv_ - the test set, you must predict the toxicity probabilities for these comments. To deter hand labeling, the test set contains some comments which are not included in scoring.
* _sample\_submission.csv_ - a sample submission file in the correct format

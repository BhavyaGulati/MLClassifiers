# MLClassifiers - Supervised Learning
Given a set of emails, written by 2 users, objective is to classify the emails as written by one person or the other based only on the text of the email.

## Naive Bayes:
Acuuracy came out to be 0.97 
Naive Bayes learners and classifiers can be extremely fast compared to more sophisticated methods. The decoupling of the class conditional feature distributions means that each distribution can be independently estimated as a one dimensional distribution. This in turn helps to alleviate problems stemming from the curse of dimensionality.

Particularly here, Naive bayes does work really well with Text. But with phrases which have multiple words which join to form a differrent meaning might not be best implemented by naive bayes.
## SVM:
### The advantages of support vector machines are:
Effective in high dimensional spaces.
Still effective in cases where number of dimensions is greater than the number of samples.
Uses a subset of training points in the decision function (called support vectors), so it is also memory efficient.
Versatile: different Kernel functions can be specified for the decision function. Common kernels are provided, but it is also possible to specify custom kernels.

### The disadvantages of support vector machines include:
If the number of features is much greater than the number of samples, avoid over-fitting in choosing Kernel functions and regularization term is crucial.
SVMs do not directly provide probability estimates, these are calculated using an expensive five-fold cross-validation

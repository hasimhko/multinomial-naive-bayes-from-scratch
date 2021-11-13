# Multinomial Naive Bayes Classifier with Dirichlet Prior
## Bag-of-Words Representation and Multinomial Naive Bayes Model

The dataset is split into training (700 emails) and test (260 emails) datasets:
- train-features.txt
- train-labels.txt
- test-features.txt
- test-labels.txt

In the feature files, each row contains the feature vector for an email. The j-th term in a row i is the number of occurrences of the j-th vocabulary word in the i-th email. The size of the vocabulary is 2500. The label files include the ground truth label for the corresponding email, the order of the emails (rows) are the same as the features file. That is the i-th row in the files corresponds to the same email document. The labels are indicated by 1 or 0, 1 stands for a spam email and 0 stands for the nonspam email.

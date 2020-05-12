# Mushroom-Classification-using-Naive-Bayes-Classifier
In this task, the data-set used, comprises of two types of Mushrooms Type p and Type e and their features.

Dataset consists of 8124 Samples and each sample consists of 23 Features.

Classification of samples is done by Naive bayes Classifier.
Following tasks were Performed during the classification task:
- Reading Data
- Converting Categorical data to Numerical Data using LabelEncoder()
- Data Splitting into Training and Testing Data
- Then the classifier is build which will be operable after implementing few functions that are required for working of Classifier:
  - Function prior_prob() that computes Prior Probability
  - Function cond_prob() that computes Conditional probability 
  - Fuction predict() that predicts the type og mushroom with the help of above two functions
- Lastly accuracy of the classifier is tested by defining a score function.
The max accuracy that was achieved on this dataset was 99.815%.

To run the code, please make sure that the latest version of Python, Jupyter and aforementioned libraries are installed in your system.

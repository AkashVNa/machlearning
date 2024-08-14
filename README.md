Aim:
  The objective of this assessment is to evaluate your understanding and ability to apply supervised learning techniques to a real-world dataset.

Dataset:
  The breast cancer dataset available in the sklearn library.

Data Preprocessing:
  Load the breast cancer dataset from sklearn.
  The dataset consists of 30 features and 569 entries per column.
  No null values,duplicate values are present in the dataset.
  All features are of float type and no object feature is present.
  Outliers are supposed to be present on initial observation.
  Ouliers are removed using Inter quartile range method wth capping with median values.
  Features are scaled using standard scaler.
  Target variable is imported and it is a binomal variable with values 0 and 1.

Algorithms used for the dataset:
  1. Logistic Regression
  2. Decision Tree Classifier
  3. Random Forest Classifier
  4. Support Vector Machine (SVM)
  5. k-Nearest Neighbors (k-NN)

Graphs Used:
  Boxplots to identify outliers in columns.
  Heat maps to find the accuracy of algorithms.
  Line plot to compare acccuracy score.

Model Comparison:
  Accuracy Scores are obtained from each algorithm and this is used to compare the models.
  Confusion matrix, Classification report of every model is obtained.

Inferences:
  Logistic Regression is the best algorithm for the gven dataset with approximate accuracy of 98.6%.
  Decision Tree Classifier performed worst of the given algorithms wth approximate accuracy of 93%.
  The dataset is of too small a size to implement a reliable machine learning method.

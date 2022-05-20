# Supervised Learning: Classification with Random Forest and KNeighborsClassifier

For the classification task, we used the famous handwritten digit dataset from the sklearn.datasets package called mnist_784.

We used Random Forest models and KNeighborsClassifier for this task. To adjust the aforementioned models, we used GridSearchCV to select the best parameters. In the evaluation of the models, the accuracy, recall, precision, f1_score, and the confusion matrix were used.

Activities that were done:
Try to achieve an accuracy above 97% in the test set with KNeighborsClassifier, adjusting the 'weights' and 'n_neighbors' hyperparameters with the grid search;<br>
Write a function that modifies only the training images of the dataset by shifting one pixel in each image in any direction (left, right, up, or down), that is, for each image in the training set, four images offsets are created and add them to the training set. Then train your best classifier with the new augmented set. Finally, measure the performance of the model through the metrics of accuracy, precision, recall, and F1-score. Tip: Investigate the shift() function of the scipy.ndimage.interpolation module to shift the pixel.

We managed to achieve 97% accuracy with KNeighborsClassifier.<br>
Modifying the training images of the dataset by shifting one pixel and we trained with our best model, the result was not what we expected, which was to increase the performance of the model.

# Support-Vector-Machine-Decision-Boundary

## (a) i) Fit a support vector classifier to the training data with cost parameter chosen optimally using 10-fold cross-validation. Summarize key features of the fit. ii) Evaluate its performance on the test data. iii) Summarize your results.

## i) Fit a support vector classifier to the training data with cost parameter chosen optimally using 10-fold cross-validation

After performing a 10-Fold CV. I stored the optimal cost parameter and used it to fit a Support Vector Classifier. The decision boundaries from different Groups can be seen in the plot.

<p float="left">
  <img src="https://github.com/JaimeGoB/Support-Vector-Machine-Decision-Boundary/blob/main/data/svc_boundaries.png" width="500" height="420">
  <img src="https://github.com/JaimeGoB/Support-Vector-Machine-Decision-Boundary/blob/main/data/svc_results.png" width="300" height="420">
</p>

## ii) Evaluate its performance on the test data
![cf](https://github.com/JaimeGoB/Support-Vector-Machine-Decision-Boundary/blob/main/data/svc_confusion_matrix.png)

## iii) Summarize your results.

From the confusion matrix it is evident to see that there are only two observations from Group 1 are missclassified as Group 3.


## (b) Repeat (a) using a support vector machine with a polynomial kernel of degree two.

## i) Fit a support vector machine to the training data with cost parameter chosen optimally using 10-fold cross-validation

After performing a 10-Fold CV. I stored the optimal cost parameter and used it to fit a Support Vector Machine with polynomial kernel degree 2. The decision boundaries from different Groups can be seen in the plot.

After performing a 10-Fold CV. I stored the optimal cost parameter and used it to fit a Support Vector Classifier. The decision boundaries from different Groups can be seen in the plot.

<p float="left">
  <img src="https://github.com/JaimeGoB/Support-Vector-Machine-Decision-Boundary/blob/main/data/svm_polynomial_boundaries.png" width="500" height="420">
  <img src="https://github.com/JaimeGoB/Support-Vector-Machine-Decision-Boundary/blob/main/data/svm_polynomial_results.png" width="300" height="420">
</p>

## ii) Evaluate its performance on the test data
![cf](https://github.com/JaimeGoB/Support-Vector-Machine-Decision-Boundary/blob/main/data/svm_polynomial_confusion_matrix.png)


## iii) Summarize your results.
From the confusion matrix it is evident to see that there are many observations that are missclassified. There are only 8 observations from test correctly classified and 7 are missclassified. The SVM with kernel degree 2 does slightly better than random guessing.


## (c) Repeat (a) using a support vector machine with a radial kernel with both Gamma and cost parameter chosen optimally.

## i) Fit a support vector machine to the training data with cost parameter chosen optimally using 10-fold cross-validation

After performing a 10-Fold CV. I stored the optimal cost parameter and gamma parameter and used it to fit a Support Vector Machine. The decision boundaries from different Groups can be seen in the plot.

<p float="left">
  <img src="https://github.com/JaimeGoB/Support-Vector-Machine-Decision-Boundary/blob/main/data/svm_radial_boundaries.png" width="500" height="420">
  <img src="https://github.com/JaimeGoB/Support-Vector-Machine-Decision-Boundary/blob/main/data/svm_radial_results.png" width="300" height="420">
</p>

## ii) Evaluate its performance on the test data
![cf](https://github.com/JaimeGoB/Support-Vector-Machine-Decision-Boundary/blob/main/data/svm_polynomial_confusion_matrix.png)

## iii) Summarize your results.
From the confusion matrix it is evident to see that there is only one misclassified observation from Group 1 misclassified as Group 3. 

## (d) Compare results from the above three methods and also the method you recommended for these data in Mini Project 2. Which method would you recommend now? For this method, display the data with decision boundary superimposed.

From Mini project 2. Using QDA the observations that are misclassified are only 1 similar to SVM - Radial Decision boundary. Since the both methods provide the exact results I would recommend both SVM - Radial Decision boundary and Quadratic Discriminant Analysis.

![QDA vs SVM - Radial Kernel](https://github.com/JaimeGoB/Support-Vector-Machine-Decision-Boundary/blob/main/data/svm_vs_qda.png)

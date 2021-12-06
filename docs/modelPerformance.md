# Model Performance
## Multinomial Naive Bayes Classifier
Naive Bayes Classifier works on the basis of Bayes’ Theorem. The fundamental assumptions made are that all the features are independent of one another and contribute equally to the outcome; all are of equal importance.

### Confusion Matrix
<img src="https://github.com/abhishek-pes/DA-Project-Amazon-product-listing/blob/main/docs/images/mnb_cm.JPG" height="200">


|Accuracy Score|88.909%|
|--------------|-------|
|**Time taken for model fit**|**30s**|

## Random Forest Classification
Random Forest Classification is an example of Ensemble learning, where multiple machine learning algorithms are put together to create one bigger and better performance ML algorithm. This results in a wide diversity that generally results in a better model.Random forest adds additional randomness to the model, while growing the trees.

### Confusion Matrix
<img src="https://github.com/abhishek-pes/DA-Project-Amazon-product-listing/blob/main/docs/images/rf_cm.JPG" height="200">


|Accuracy Score|59.157%|
|--------------|-------|
|**Time taken for model fit**|**62s**|

## XGBoost (eXtreme Gradient Boosting)
XGBoost (eXtreme Gradient Boosting) is a popular supervised-learning algorithm used for regression and classification on large datasets. It uses sequentially-built shallow decision trees to provide accurate results and a highly-scalable training method that avoids overfitting.

### Confusion Matrix
<img src="https://github.com/abhishek-pes/DA-Project-Amazon-product-listing/blob/main/docs/images/xgb_cm.JPG" height="200">


|Accuracy Score|83.30%|
|--------------|-------|
|**Time taken for model fit**|**600s**|

## Support Vector Classifier
SVC is a supervised machine learning algorithm which can be used for classification or regression problems. It uses a technique called the kernel trick to transform your data and then based on these transformations it finds an optimal boundary between the possible outputs.

### Confusion Matrix
<img src="https://github.com/abhishek-pes/DA-Project-Amazon-product-listing/blob/main/docs/images/svc_cm.JPG" height="200">


|Accuracy Score|88.230%|
|--------------|-------|
|**Time taken for model fit**|**120s**|

## Perceptron Model
The Perceptron Classifier is a linear algorithm that can be applied to binary/multi classification tasks. An perceptron acts as an neuron that performs the actions as that of an human like functions. The perceptron works  as a layer based where it is learning something new about the data.

### Confusion Matrix
<img src="https://github.com/abhishek-pes/DA-Project-Amazon-product-listing/blob/main/docs/images/percep_cm.JPG" height="200">


|Accuracy Score|87.909%|
|--------------|-------|
|**Time taken for model fit**|**26s**|

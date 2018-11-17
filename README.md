# PyTorch Scholarship Challenge Notes

# Intoduction to Neural Networks

Neural networks
- given some data, the neural networks will look for the best line that separates them.

How do we find this line?
- y = w1x1 + b

Perceptron
- building block of neural networks

Perceptron trick
- For a point with coordinates with (p,q), label y, and prediction given by the equation y_hat = step(w1x1 + w2x2 + b)
- if the point is classified as positive but has a negative label, subtract ap, aq, and a from w1, w2 and b respectively
- if the point is classified as negative but has a positive label, add ap, aq, and a from w1, w2 and b respectively

Error Functions
- is something that tells us how far we are from solution

Log-loss Error Function
- measures the performance of a classification model where the prediction input is a probability value between 0 and 1. 

Sigmoid function
- is defined as sigmoid(x) = 1/(1+e-x).

Softmax
- logistic function used for multiclass classification

OneHot Encoding
- turns numerical data into catergorical data

Maximum likelihood
- a method used in estimating the parameters of a statistical model and for fitting a statistical model to data.

Cross Entropy
- error function for multiclass classification

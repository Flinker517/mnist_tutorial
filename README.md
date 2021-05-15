# mnist_tutorial
A tutorial for MNIST handwritten digit classification using sklearn and PyTorch.

# Code structure
* [`numpy_matplotlib_sklearn.ipynb`](numpy_matplotlib_sklearn.ipynb): for numpy, matplotlib and sklearn.
* [`pytorch.ipynb`](pytorch.ipynb): for pytorch.
* [`keras.ipynb`](keras.ipynb): for keras (not used).

# Requirements (default)
Code tested on following environments, other version should also work:
* python 3.6.3
* numpy 1.13.3
* matplotlib 2.1.0
* sklearn 0.19.1
* pytorch 0.4.1

# Result
For numpy_matplotlib_sklearn.ipynb
* logistic regression: Training accuracy is 95.30%, testing accuracy is 88.10%.
* Naive bayes (Bernoulli): Training accuracy is 81.78%, testing accuracy is 80.90%.
* Support vector machine: Training accuracy is 97.73%, testing accuracy is 85.40%.
* Adjusted SVM: for LinearSVC with loss='hinge', training accuracy is 95.92% and testing accuracy is 86.80%;for NuSVC, training accuracy is 88.10% and testing accuracy is 86.50%;for SVC, training accuracy is 91.25% and testing accuracy is 89.60%.
For pytorch.py
* With epoch = 10, learing rate = 0.001, batch size = 128 and lenet5, training accuracy is 99.72% and test accuracy is 98.96%.
**MNIST Hand Written Digit classifier**

This is a multiclass(more specifically 10 class) classifiaction problem.

The MNIST database of handwritten digits, 
available from this UCI page ,
has a training set of 60,000 examples, and a test set of 10,000 examples. 
It is a subset of a larger set available from NIST.
We can use the above dataset or use it from keras dataset(without downloading !).We have used the latter approach.

In this project we have used two models :
M1 - 3 ConvLayer with maxpooling.
M2 - 5 ConvLayer with dropout.

**We found out that we got better results with second model and more better generalisation due to Dropout Layer.**

We got 99.2% accuracy with model 2 and 99.1% accuracy with model 1 but we found model1 to be overfitting on the data.


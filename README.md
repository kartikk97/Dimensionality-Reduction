# Dimension Reduction on MNIST

Dimensionality Reduction is a powerful technique that is widely used in data analytics and data science to help visualize data, select good features, and to train models efficiently. We use dimensionality reduction to take higher-dimensional data and represent it in a lower dimension.

![](d1.JPG)

## Introduction -

 **We humans can visualise 2D, 3D data or images. But what if the data contains 4 dimensions? or 5 dimensions or even 100,200,500 dimensions?     
 So in such cases with the help of PCA and t-SNE we will be working with MNIST data which has 784 dimensions and are going to reduce to 2D form.**

### Packages used - 
*Multiple packages were used* in the notenook. These packages were imported into python 3 version. The packages are:
* Numpy
* Pandas
* Seaborn
* Matplotlib
* warnings
* scipy
* sklearn


### MNIST(Mixed National Institute of Standards and Technology)

MNIST is a simple computer vision dataset. It consists of 28x28 pixel images of handwritten digits, such as:

![](mnist_digits.JPG)

Every MNIST data point, every image, can be thought of as an array of numbers describing how dark each pixel is. For example, we might think of 1 as something like:

![](dim_digits.JPG)

Since each image has 28 by 28 pixels, we get a **28x28** array. We can flatten each array into a **28∗28=784** dimensional vector. Each component of the vector is a value between zero and one describing the intensity of the pixel. Thus, we generally think of **MNIST as being a collection of 784-dimensional vectors.**
**Data Set-** https://www.kaggle.com/ngbolin/mnist-dataset-digit-recognizer/data

### Methods used - 

* **Principal Component Analysis ( PCA )** - Unsupervised, linear method.
* **t-distributed Stochastic Neighbour Embedding (t-SNE)** - Supervised, Nonlinear method.

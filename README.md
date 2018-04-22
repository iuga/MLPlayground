# Machine Learning Playground
In this repo, I'm collecting several Statistical Learning experiments in R or Python with Keras/Tensorflow. Most of this won't be useful to others but this is the place where I will document my journey into some specific topics in Statistical, Machine and Deep Learning.

## Contents

## Statistical Learning
Provides an accessible overview of the field of the statistical learning. An essential toolset for making sense og the vast and complex concepts that emerge in the field.
- [Statistical Learning: Introduction](statistical_learning/introduction.ipynb) 

### Autoencoders
The key element of an autoencoder is the “information bottleneck”, that is, the autoencoder is forced to form a representation at the intermediate hidden layer that has a smaller number of variables than the input. This forces the autoencoder to keep only the components that are useful for reconstructing the common features of the inputs, and to reject any components that are not common features. As a result, an autoencoder will tend to learn a representation in the hidden layer that rejects noise from the input, and act in a manner similar to a nonlinear PCA.
- [MNIST: Simple autoencoder](autoencoders/)
- [MNIST: Convolutional autoencoder](autoencoders/)
- [MNIST: Variational autoencoder](autoencoders/)

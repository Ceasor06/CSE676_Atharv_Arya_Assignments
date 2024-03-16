"CSE676_Ass_1.ipynb" file contains the code for Assignment1, in which I designed an FNN for MNIST classification and the plot training and test loss is also included in the ipynb file.

In this assignment, I've implemented FNN using Pytorch and torchvision through which I've loaded the MNIST dataset. My architecture contains 1 input layer, an output layer (linear layer with LogSoftmax) of ten neurons and two hidden layers in between

I've defined a class "FNN" for my FNN where I've created all the layers that are required for it to work, defined Loss function and an optimizer, then iterated over the training dataset in batches, performed the forward and backward passes and updated the weights, then evaluated the model's performance on the test dataset. Then using matplotlib, the training and test losses are plotted agianst the number of iterations.

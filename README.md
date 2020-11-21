# Deeplearning-Model
This is a deep learning model that incorporates logisitc regression algorithm to check whether a image is of a cat or no. The algorithm follows two steps the : -
1. The forward propagation step - in this step first the parameters are initialised and the vector of pixels is flattened. Then using the features and paratmeters the probablity of the image to be a cat image is calculated using the sigmoid fuunction.This process is then repeated for all the values in the dataset.Thenn the loss is calculated for each value in dataset which in turn gives the loss for the entire model using the cost function
2. The backward propagation step - In this step we are going to calculate the the maximum slope at a point on the cost function for a particular parameter and fix the other to zero till we reacht the global minima. This process is called gradient descend.

Technologies used - Juypter Notebook, Numpy

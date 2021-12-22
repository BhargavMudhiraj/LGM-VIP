## MNIST Handwritten Digit Classifier

An implementation of multilayer neural network using keras tensorflow with an accuracy over 98%.

## Dataset

The system developed was trained on MNIST dataset. The dataset consists of 70,000 handwritten digit image samples and is partitioned to two sets containing 60,000 samples and 10,000 samples respectively. The larger of the sets is used for training and the smaller is utilized for testing.

The training set consisting of 60,000 images is further partitioned during training to form the validation set. To this end, 20% of the data i.e. 12,000 image samples have been repurposed to form the validation set.

## Prerequisites

* OpenCV
* Python 3.5

### Structure of Neural Network:
A neural network is made up by stacking layers of neurons, and is defined by the weights 
of connections and biases of neurons. Activations are a result dependent on a certain input.

This structure is known as a feedforward architecture because the connections in the network flow forward from the input layer to the output layer without any feedback loops. In this figure:

* The input layer contains the predictors.
* The hidden layer contains unobservable nodes, or units. The value of each hidden unit is some function of the predictors; the exact form of the function depends in part upon the network type and in part upon user-controllable specifications.
* The output layer contains the responses. Since the history of default is a categorical variable with two categories, it is recoded as two indicator variables. Each output unit is some function of the hidden units. Again, the exact form of the function depends in part on the network type and in part on user-controllable specifications.
![Small Labelled Neural Network](http://i.imgur.com/HdfentB.png)

## Output:
<img src="https://github.com/BhargavMudhiraj/LGMVIP-DATASCIENCE/blob/main/Task-3/Ouput/output.png" width= "50%">

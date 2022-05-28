This report documents implementation of a deep neural network with an input layer, three hidden layers with ReLu non-linear activation and an output or classification layer.

We trained a neural network to classify images from the CIFAR-10 dataset. This report documents the training process investigating the effects of the following hyperparameter settings on accuracy:

Batch size,
Depth,
Width,
Convolutional filter size,
Dropout,
Batchnorm,
Max pool,
Tanh non-linearity,
Optimiser,
Weights initialization,
Regularisation (weight decay),
Learning rate,
Learning rate scheduler.

Further we explored the number of epochs, momentum and normalization and noted the model accuracy on 10000 test images along with final training loss.


Please refer to Github commits for each iteration of the exploration.

Ultimately each of these hyperparameters when adjusted individually as defined in the assignment yielded no notable improvement in accuracy from baseline.

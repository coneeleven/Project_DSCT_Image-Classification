# Springboard Data Science Career Track Capstone_2

The CIFAR10.ipynb notebook is an image classification of the CIFAR-10 image data. 

Techniques used include baseline modeling and convolutional neural network modeling using Keras wrapped Tensorflow. An AWS p2.xlarge instance with a GPU was used for training these models.

Also included are the final report and slide deck as required by the Springboard project guidelines.

This project encompassed three phases of models. First, a baseline model using a single 2D matrix of pixel values. Accuracy results were just over 47% for all three configurations. Second, a simple convolutional model with 6 hidden layers yielded between 72-74% accuracy while varying only the learning rate. Lastly, a (moderately) deep CNN with 16 hidden layers and up to 2.5MM parameters yielded accuracy values over 84%.

Tools used include Keras, Tensorflow, and an AWS instance with a GPU to accelerate training time. The longest model took over 4 hours to train using the GPU, and from my observations this was about 40X faster than the CPU in my laptop.

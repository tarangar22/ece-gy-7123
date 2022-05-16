# ECE-GY-7123: Deep Learning

This repo consists of tasks undertaken during the duration of the Deep Learning course for Spring'22.

# Mini-Project 1
The ResNet.ipynb file consists of the training procedure for achieving a 90% accuracy on the CIFAR-10 dataset with a constraint of having <5M parameters in the Convolutional Neural Network as the result of Mini-Project 1.

# Mini-Project 2
The GRU.ipynb and GAN.ipynb files consist of the training procedures for generating MNIST images from AudioMNIST speech and consists of the AutoEncoder and DCGAN parts, respectively. 

This is intended to be a temporary representation of the two parts of the problem statement and is the result of Mini-Project 2. The necessary further changes will be reflected upon integration of both modules for the resultant output of Mini-project 3. 

# Mini-Project 3
The GRU.ipynb has been changed from an AutoEncoder to a Reccurent Classifier for AudioMNIST while achieving a 99.% accuracy. while DCGAN.ipynb has an updated GAN with better efficiency during training and improved image generation quality.

Apart from the above, a UTIL.ipynb has been added to extract MFCC features and into tensors to avoid delay with DataLoader. EVAL.ipynb consists of the final saved module with the weights for both models being used to solve the task of Speech-to-Image.

# Instructions to run Mini-Project 3
Run UTIL.py to process AudioMNIST subset and save MFCC dataset as Tensor locally. Run GRU.ipynb and DCGAN.ipynb to obtain weights for both models. Run EVAL.py to obtain final output. For ease of verification, both model weights are saved.

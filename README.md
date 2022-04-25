# ECE-GY-7123: Deep Learning

This repo consists of tasks undertaken during the duration of the Deep Learning course for Spring'22.

# Mini-Project 1
The ResNet.ipynb file consists of the training procedure for achieving a 90% accuracy on the CIFAR-10 dataset with a constraint of having <5M parameters in the Convolutional Neural Network as the result of Mini-Project 1.

The model consists of 3 Convolutional layers starting with 128 channels and kernel size 3. Training consisted of using CrossEntropyLoss with label smoothing and an ADAM optimizer with Weight Decay.

# Mini-Project 2
The GRU.ipynb and GAN.ipynb files consist of the training procedures for generating MNIST images from AudioMNIST speech and consists of the AutoEncoder and DCGAN parts, respectively. 

This is intended to be a temporary representation of the two parts of the problem statement and is the result of Mini-Project 2. The necessary further changes will be reflected upon integration of both modules for the resultant output of Mini-project 3. 

The AutoEncoder consists of an Attention-based Decoder with MFCC transforms applied on the audio input. The training was conducted through a KL Divergence Loss and ADAM optimizer. 

The DCGAN consists of a Discriminator of 4 layers starting with 64 channels and kernel size 4 while the Generator is the inverted Deconvolution Network of the Dicriminator. The model was trained using BinaryCrossEntropyLoss with label smoothing and ADAM optimizer with Weight Decay.

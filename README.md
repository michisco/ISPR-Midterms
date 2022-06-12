# ISPR-Midterms

## Midterm 1

Implement the convolution of a Laplacian of a Gaussian blob (LoG) detector with an image and apply it to 3-4 images of your choice from the dataset (possibly from different thematic classes). Do not use library functions for implementing the convolution or to generate the LoG filter. Implement your own and show the code (the interesting bits at least)! The function you implement should be able to run the LoG for different choices of the scale parameter, which is passed as an input argument. Show the results of your code on the 3-4 example images, for different choices of the scale parameter (sigma).

## Midterm 2

Implement from scratch an RBM and apply it to DSET3. The RBM should be implemented fully by you (both CD-1 training and inference steps) but you are free to use library functions for the rest (e.g. image loading and management, etc.).

1. Train an RBM with a number of hidden neurons selected by you (single layer) on the MNIST data (use the training set split provided by the website).
2. Use the trained RBM to encode all the images using the corresponding activation of the hidden neurons.
3. Train a simple classifier (e.g. any simple classifier in scikit) to recognize the MNIST digits using as inputs their encoding obtained at step 2. Use the standard training/test split. Show a performance metric of your choice in the presentation/handout.

## Midterm 3

Implement your own convolutional network, deciding how many layers, the type of layers and how they are interleaved, the type of pooling, the use of residual connections, etc. Discuss why you made each choice a provide performance results of your CNN on CIFAR-10.  

Now that your network is trained, you might try an adversarial attack to it. Try the simple Fast Gradient Sign method, generating one (or more) adversarial examples starting from one (or more) CIFAR-10 test images. It is up to you to decide if you want to implement the attack on your own or use one of the available libraries (e.g. foolbox,  CleverHans, ...). Display the original image, the adversarial noise and the final adversarial example.  

## Midterm 4

Presentation of the paper [Policy distillation](https://arxiv.org/abs/1511.06295)

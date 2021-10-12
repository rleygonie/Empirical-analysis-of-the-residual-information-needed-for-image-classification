# Empirical-analysis-of-the-residual-informationneeded-for-image-classification


This file contains the main scripts of the experiments carried out for the empirical analysis of the residual information necessary for the classification of images.

The Image generation.ipynb file contains the functions for:
- generate QR Codes from strings of 150 characters drawn randomly
- generate images from QR Codes containing facebook or twitter logos, whole or split in two, positioned randomly or not.
- generate images from QR Codes to which are added the twitter or facebook logos split in two, positioned randomly so that a certain distance is respected.
- Random noise addition in the images (from 10% to 100%) of the total surface. Noise is the random assignment of a color to a pixel in the image.

The Train and Test.ipynb file contains the training and testing scripts for the LeNet5 model.

The experimental scripts on the MNIST dataset are not present because they repeat exactly the same logic as those with the logos.

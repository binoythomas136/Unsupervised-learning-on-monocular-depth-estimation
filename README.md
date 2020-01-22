# Unsupervised-learning-on-monocular-depth-estimation
We show how a convolutional neural network can be used to learn to perform single image depth estimation with no available ground truth depth data. We tried to find disparity between the left and the right poses of an image from the KITTI 2015 dataset. We obtained considerably better results compared to other supervised learning methods. We found out that in order to obtain better results, it is not only important to consider the image reconstruction loss but also the training loss. We were able to achieve very good results by training the system with a large dataset and using a large number of epochs to train the system

models_resnet.py is the code for the model that we used for obtaining the results.

The report describes the project and the results obtained.

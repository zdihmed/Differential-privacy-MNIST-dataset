# Implementing-differential-privacy-into-the-MNIST-dataset: 

In this project we implement differential privacy on the MNIST dataset, then, we train a learning model on the noisy dataset generated after implementing differential privacy. In another word, we train a learning model on a noisy MNIST dataset. The noisy dataset is generated after adding Gaussian noise to each image of the dataset. 



mainMnistNormalNoise.py            : This file contains the main function for:
                                        1) pre-processing the MNIST dataset, i.e., normalizing the dataset and adding Normal noise.
                                        2) training the learning model located in the file Net.py

Net.py                             : This file contains the designed learning model
TransformNormalDistribution.py     : This file contains the transform for adding the Normal noise to the original dataset before starting the training


# Implementing MLPs with Keras and Tensorflow

## Overview

This repository contains my implementation of multilayer perceptron (MLP) neural networks using Keras and Tensorflow. The goal of this project was to investigate and experiment with MLPs on the Credit Approval dataset from the UCI Machine Learning Repository. 

The Credit Approval dataset contains information on credit card applications and includes both numerical and categorical features. Before training the MLPs, the dataset was preprocessed, with missing values filled with mode and means, normalization, outlier detection with K-Means, and conversion of categorical features to numerical. The preprocessed dataset was then split into training and testing sets.

In this project, I implemented MLPs using both hand-tuning and Keras tools for hyperparameter tuning. Specifically, I experimented with different activation functions, hidden layer sizes, and learning rates to find the best combination of hyperparameters for the MLP. I also employed techniques to reduce overfitting, such as regularization and early stopping, and tested the performance of the MLP on the testing set.

This project was completed as part of the "Neural Networks" (changed to "Neural Computing and Deep Learning") course at Amirkabir University of Technology (AUT) in Tehran, Iran, taught by Professor Reza Safabakhsh(<safa@aut.ac.ir>). I took this course during my Master of Science degree in Computer Engineering at AUT in Spring 2022.

![Output](/plot.png)

## Dataset

The Credit Approval dataset used in this project is publicly available on the UCI Machine Learning Repository. The dataset contains 690 instances and 15 attributes, including both numerical and categorical features. The dataset was preprocessed using Python and the Pandas library.

## Contributions

Contributions to the project are welcome. If you find a bug or want to suggest an improvement, please open an issue or submit a pull request.

## License

This project is licensed under the GPL-3.0 License. Please see the LICENSE file for more information.

## Contact

If you have any questions or want to get in touch with me, you can send an email to <m.ebadpour@aut.ac.ir> or open a conversation via pull request on GitHub. I hope this project can be helpful to others who are interested in learning more about neural networks and deep learning.

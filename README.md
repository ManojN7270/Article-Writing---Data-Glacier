# Article-Writing-Data-Glacier

Project Goal:

This project aims to build a neural network model to solve the EMNIST classification problem. As deep neural networks are widely used in various domains, such as computer vision, natural language processing and medical image analysis, how to create a proper neural network to achieve a specific task has become very important. 

Dataset Introduction:

In the project, we use the EMNIST  (Extended MNIST) dataset (https://www.kaggle.com/datasets/crawford/emnistLinks to an external site.), which is a set of handwritten character digits derived from the NIST Special Database 19 and converted to a 28x28 pixel image format and dataset structure that directly matches the MNIST dataset.

Due to the EMNIST dataset including 6 different splits, we selected the “Balanced” dataset, which addressed the balance issues in the “ByClass” and “ByMerge” datasets. It is derived from the “ByMerge” dataset to reduce misclassification errors due to capital and lower-case letters and also has an equal number of samples per class. The “Balanced” dataset information is as follows:

Train: 112,800
Test: 18,800
Total: 131,600
Classes: 47 (balanced)

This repository contains a project on satellite image classification using Convolutional Neural Networks (CNN). The model is trained and evaluated using the DeepSat SAT-4 dataset, which consists of satellite imagery across multiple classes, helping in tasks such as land cover classification.

**Dataset**

Name: DeepSat SAT-4
Source: Kaggle - DeepSat SAT-4
https://www.kaggle.com/datasets/crawford/deepsat-sat4

**Description:** 

The SAT-4 dataset contains 500,000 labeled image patches from satellite imagery. The images are classified into four classes: barren land, trees, grassland, and a class that combines various other land cover types. Each image patch is 28x28 pixels and consists of 4 channels (red, green, blue, near-infrared).
Project Overview

**Objective:** Classify satellite images into different land cover categories using a CNN model.
**Tools & Libraries:** TensorFlow/Keras, NumPy, Pandas, Matplotlib, and Scikit-learn.
**Dataset Size:** The SAT-4 dataset includes 400,000 training samples and 100,000 testing samples, each having 4 spectral bands (RGB + NIR).


**Features**
Data preprocessing and augmentation techniques
CNN architecture design and training
Model evaluation and performance metrics
Visualization of classification results

**How to Use**
Download the dataset from Kaggle using the provided link.
Follow the steps in the notebook to preprocess the data and train the model.
Evaluate the model's performance on the test dataset.

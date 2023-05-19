# Deepfake-Detection

This project is a part of the course ```CS517(Digital Image Processing)```

It's a collaborative project between:
1. Arnav Kharbanda
2. Keshav Aggarwal
3. Yashasav Prajapati

## Introduction
The project aims to detect deepfake images. We used tensorflow and keras to build the model. Inorder to train the model efficiently, we used early stopping and model checkpointing. We also used data augmentation[this was done locally] to increase the size of the dataset.

## Dataset and Problem Statement
The dataset and problem statement was taken from the following link:
https://iplab.dmi.unict.it/deepfakechallenge/

We focused on the Task-1 of the problem statement. 

## How to Run
1. Clone the repository
2. Take the ``main.ipynb`` file from the code directory and upload the notebook on ``Google Colab``.
3. Make a folder on Google Colab named "``Deepfake``" and a subfolder inside it named "``Dataset``".
4. Now run the notebook cell by cell, the dataset will be downloaded and extracted and arranged into folders. The model will be trained and tested and the results will be displayed.
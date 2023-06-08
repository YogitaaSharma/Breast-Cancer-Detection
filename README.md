# Breast-Cancer-Detection

## Introduction
This repository contains code and resources for detecting invasive ductal carcinoma (IDC) in breast cancer histopathology images using deep learning Convolutional Neural Network Algorithm. The goal is to accurately identify and categorize breast cancer subtypes, specifically focusing on IDC, which is the most common form of breast cancer.

## Dataset
The dataset used for this project consists of 277,524 50x50 pixel RGB digital image patches. These patches were derived from 162 H&E-stained breast histopathology samples. The images are unlabeled, and the task is to identify patches that contain cells characteristic of invasive ductal carcinoma (labeled as "1").

### To access the dataset, please download it from Kaggle using the following link:
[https://www.kaggle.com/code/paultimothymooney/predict-idc-in-breast-cancer-histology-images/input]

## Repository Structure
The repository has the following structure:

- data/: This directory should contain the dataset downloaded from Kaggle.
- notebooks/: Jupyter notebooks for data exploration, preprocessing, model training, and evaluation.
- README.md: This file, providing an overview of the project.

## Getting Started

To get started with this project, follow these steps:

- Download the dataset from the Kaggle link provided above and place it in the data/ directory.
- Set up a Python environment with the required dependencies. You can use pip to install the necessary packages listed in the requirements.txt file.
- Explore the Jupyter notebooks in the notebooks/ directory to understand the data and the implemented workflows.
- Use the provided notebooks or scripts in the scripts/ directory to preprocess the data, train models, and make predictions.
- Customize and modify the code as needed for your specific use case.

## References
- Original Dataset: Predicting IDC in Breast Cancer Histology Images
- Research Paper: Spatial Fusion Convolutional Networks for Invasive Ductal Carcinoma Classification
- Conference Paper: Spatially Invariant Unsupervised Tissue Analysis Using Stain Normalization and Cell Density Estimation

## License
The code and resources in this repository are provided under the MIT License. Feel free to use and modify them according to your needs.

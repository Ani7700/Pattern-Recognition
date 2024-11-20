# Package Overview

This package provides implementations of key machine learning and deep learning techniques, including PCA, LDA, GMM, and CNN. The package is designed for classification tasks using a custom dataset of 25 categories and a set of 10 selfies.

## Package Structure

PCA: Principal Component Analysis implementation for dimensionality reduction and visualization.
LDA: Linear Discriminant Analysis for feature extraction and classification.
GMM: Gaussian Mixture Model for clustering tasks on both raw and reduced-dimension data.
CNN: Convolutional Neural Network for image classification, with examples of training, evaluation, and visualization.
data: Contains 25 categories of data selected for the task.
selfie: Contains 10 selfies for additional testing and analysis.

### How to run the codes

To ensure the environments are properly installed, first run the following code in conda virtual environment:

```bash
conda create -n ml_env python=3.11
conda activate ml_env
pip install cv2
pip install sklearn
pip install matplotlib
pip install tensorflow
```

Each code is written in Python with Jupyter Notebook and to run the codes just click on the execute button on each code block.

1.Open the Jupyter Notebook:
Each algorithm (PCA, LDA, GMM, CNN) is implemented as a standalone Python notebook.
To run a specific notebook, navigate to its folder and open it using Jupyter Notebook:

```bash
jupyter notebook
```

2.Execute the Code Blocks:
The code is organized into blocks. Simply click the Run button for each block sequentially.
Ensure the data and selfie folders are in the correct directory structure as specified.

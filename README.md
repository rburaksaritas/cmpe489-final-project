# CMPE489 Final Project - Replication Study of "Multitask Learning Via Interleaving: A Neural Network Investigation"

## Overview
This project investigates multitask learning using interleaving techniques that are described by Mayo et al. in their paper ["Multitask Learning Via Interleaving: A Neural Network Investigation"](https://escholarship.org/uc/item/3tb956hb). The experiments focus on understanding how interleaving different tasks affects the learning process and performance of neural networks. 

## Project Structure
The notebook is divided into several sections, each focusing on different datasets and interleaving strategies:

1. **Setup & Definitions**:
   - Import necessary libraries.
   - Define classes and functions required for the experiments.

2. **Dividing a Single Dataset**:
   - **CIFAR5 + CIFAR5 (paper)**: Experiments using subsets of the CIFAR-10 dataset.
   - **STL5 + STL5 (alternative)**: Experiments using subsets of the STL-10 dataset.
   - **MNIST5 + MNIST5 (alternative)**: Experiments using subsets of the MNIST dataset.

3. **Two Different Datasets**:
   - **CIFAR5 + SVHN5**: Combines subsets from CIFAR-10 and SVHN datasets.
   - **MNIST5 + FashionMNIST5**: Combines subsets from MNIST and Fashion-MNIST datasets.

4. **Extended Training in Interleaved and Blocked Settings**:
   - Compare interleaved training with blocked training.

5. **Extra: Interleaving Three Tasks**:
   - **CIFAR3 + CIFAR3 + CIFAR3**: Uses three subsets of CIFAR-10.
   - **MNIST3 + MNIST3 + FashionMNIST3**: Combines subsets from MNIST and Fashion-MNIST.

## Setup
To run this notebook, you need to have the following libraries installed:
```
torch
torchvision
matplotlib
tqdm
```

You can install them using pip:
```bash
pip install torch torchvision matplotlib tqdm
```

## Running the Notebook
1. Clone this repository to your local machine.
2. Open the notebook `main.ipynb` in Jupyter Notebook or Jupyter Lab.
3. Run the cells sequentially to reproduce the experiments.

## Results
The results of the experiments, including visualizations and performance metrics, are displayed within the notebook. These results provide insights into how different interleaving strategies impact multitask learning.

## Authors
- Efekan Kavalcı
- Ramazan Burak Sarıtaş
- Ali Alperen Sönmez

## Course
This project is a final submission for CMPE489: Cognitive Science.

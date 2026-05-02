# Chem-C142-Final-Project
This project aims to develop and train a Deep Convolutional Generative Adversarial Network (DCGAN) style architecture and an Atomic Neural Network (ANI) to predict molecular potential energy surfaces. By leveraging Atomic Environment Vectors (AEVs), the model learns to map the spatial orientation of atoms (H, C, N, O) to their respective chemical energies.

## Requirements
To run this notebook, you will need a Python environment (preferably conda) with the following dependencies:
- __Python 3.8+__
- __PyTorch__ (CUDA support recommended for GPU acceleration)
- __TorchANI__: A PyTorch-based library for training
- __ANIh5py__: For handling the ANI dataset format
- __tqdm, numpy, matplotlib__: For data processing and visualization

## Dataset Preparation
You must have the `ani_dataset_gdb_s01_to_s04.h5` file available. 
### Installation
Create a working directory:
'''Bash
mkdir -p /global/scratch/users/[USER_NAME]/[DIR_NAME]
cd /global/scratch/users/[USER_NAME]/[DIR_NAME]
'''
Set up the environment:
'''Bash
pip install torch torchani h5py tqdm matplotlib
'''

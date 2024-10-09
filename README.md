Animal Image Classification using PyTorch and Lightning
Overview
This project implements an image classification model to classify different bird species using PyTorch and Lightning.
It uses a custom dataset loader and pretrained models for efficient training and testing.

Dataset
Images of 9 bird species, including duck, eagle, flamingo, hawk, owl, peacock, penguin, and more.
Stored in separate subfolders (e.g., duck/, eagle/).
Dataset format: .png
Total images: 1729
Features
Data preprocessing: resizing, cropping, and normalization.
Pretrained models from torchvision.models for transfer learning.
Modular training using PyTorch Lightning.

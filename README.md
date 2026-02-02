# Brain Tumor Segmentation and Classification

A deep learning project for MRI-based brain tumor segmentation and classification using U-Net and Attention U-Net architectures.

## Overview

This project was developed as part of **CSE428: Image Processing & Machine Learning Lab (Fall 2025)**.  
It implements an end-to-end pipeline for medical image segmentation and classification, focusing on accuracy, interpretability, and model performance.

## Features

- Implemented **U-Net** and **Attention U-Net** for pixel-level segmentation of brain MRI images.  
- Added a **classifier head** to categorize tumor types from encoder features.  
- Compared **joint vs. separate** training strategies for segmentation and classification tasks.  
- Evaluated model performance using **mIoU**, **Dice coefficient**, **accuracy**, **precision**, **recall**, and **F1-score**.  
- Visualized segmentation masks and performance curves for analysis and presentation.

## Dataset

**Dataset:** [BRISC 2025 Brain MRI Dataset](https://www.kaggle.com/datasets/briscdataset/brisc2025?resource=download)

## Technologies Used

- **Language:** Python  
- **Frameworks:** TensorFlow, Keras  
- **Libraries:** NumPy, scikit-learn, OpenCV, Matplotlib  

## Methodology

1. Preprocessed MRI images with resizing, normalization, and augmentation.  
2. Trained **U-Net** for segmentation and measured baseline performance.  
3. Enhanced model using **Attention U-Net** to improve focus on tumor regions.  
4. Attached a **classification head** to the encoder and trained both modules jointly and separately.  
5. Compared results across training, validation, and test datasets using the listed metrics.

## Author

Md. Fahim Muntasir
Final Year BSc in Computer Science, [BRAC University]  

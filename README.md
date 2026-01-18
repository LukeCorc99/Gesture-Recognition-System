# Gesture Recognition System

A convolutional neural network (CNN) project for image-based gesture recognition using the Rock-Paper-Scissors dataset. This project evaluates multiple CNN architectures and transfer learning approaches to identify the optimal model for gesture classification.

**Developed:** May 2025.

## Overview

This project implements and compares various deep learning architectures for gesture recognition:
- Basic CNN and Deeper CNN variants
- Regularization techniques (data augmentation, dropout, L2 regularization)
- Transfer learning with pre-trained models (ResNet50, VGG16)
- Impact analysis of image resolution and color space

The final model achieved **95.39% test accuracy** with strong generalization and fast inference times.


## Features

**Model Architectures Evaluated:**
- Basic CNN (2 convolutional layers)
- Deeper CNN (3 convolutional layers)
- CNN with Data Augmentation
- CNN with L2 Regularization
- CNN with Dropout
- ResNet50 (Transfer Learning)
- VGG16 (Transfer Learning + Fine-tuning)

**Analysis Performed:**
- Model comparison across multiple metrics
- Image resolution impact (50×50, 80×80, 250×250)
- Color space evaluation (RGB vs. Grayscale)
- Performance evaluation on test set

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/LukeCorc99/Gesture-Recognition-System.git
   cd Gesture-Recognition-System
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the dataset:**
   - The Rock-Paper-Scissors dataset is automatically loaded in the notebook
   - Alternatively, download from: https://www.kaggle.com/datasets/sanikamal/rock-paper-scissors-dataset


## Report

For comprehensive evaluation methodology, detailed results analysis, and architectural insights, see `GestureRecognition_Report.pdf`.

## Author

Created by Luke Corcoran [@LukeCorc99](https://github.com/LukeCorc99)
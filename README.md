# Arabic Handwritten Text Identification Using Deep Learning

This repository contains a Jupyter Notebook (`code.ipynb`) for identifying Arabic handwritten text using deep learning techniques. The project was developed as part of the Computer Vision course (ENCSS343) at Birzeit University.

## Project Overview

The goal of this project is to explore the use of Convolutional Neural Networks (CNNs) for recognizing Arabic handwritten text. The notebook includes the following:

- **Custom CNN Models**: Three different CNN architectures (CNN1, CNN2, CNN3) designed and trained from scratch.
- **Data Augmentation**: Techniques such as rotation, translation, perspective distortion, and erasing to improve model robustness.
- **Transfer Learning**: Fine-tuning a pre-trained ResNet-18 model with Squeeze-and-Excitation (SE) blocks on the AHAWP dataset.
- **Results**: Training and validation accuracy/loss plots, along with final performance metrics.

## Results

The best-performing model, **ResNet18SETransfer**, achieved a validation accuracy of **93.45%** and a test accuracy of **93.36%**. For resource-constrained environments, **CNN2** with data augmentation achieved a validation accuracy of **78.31%** and a test accuracy of **79.36%**.

## Usage

To run the code and reproduce the results:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/arabic-handwritten-text-identification.git
2. Run the .ipynb.

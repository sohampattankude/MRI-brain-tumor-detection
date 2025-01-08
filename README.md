# MRI Brain Tumor Detector
This repository contains a Convolutional Neural Network (CNN)-based project designed to detect brain tumors from MRI images. The model classifies MRI scans into two categories: "Tumor" and "Healthy."

## Table of Contents
1. Introduction
2. Dataset
3. Installation
4. Usage
5. Model Architecture
6. Results
7. Visualization
8. Contributing
9. License

## Introduction
Brain tumor detection is a critical task in medical imaging. This project leverages deep learning to automate the classification of MRI images, improving the efficiency and accuracy of diagnosis.

The project uses:

1. PyTorch for model training and evaluation.
2. A CNN-based architecture for robust image classification.

## Dataset
The dataset is organized into two categories:

Tumor: MRI images with tumors.
Healthy: MRI images without tumors.

## Dataset Directory Structure:

data/brain_tumor_dataset/

├── yes/    # Images with tumors

├── no/     # Images without tumors

Images are preprocessed to ensure uniform size (128x128 pixels) and normalized for better model performance.

## Installation
1. Clone this repository:

git clone https://github.com/yourusername/MRI-BRAIN-TUMOR-DETECTOR.git

cd MRI-BRAIN-TUMOR-DETECTOR

2. Install the required Python packages:

pip install -r requirements.txt

3. Ensure the dataset is placed in the data/brain_tumor_dataset/ directory.

## Usage
1.Open the Jupyter Notebook:

 jupyter notebook MRI-BRAIN-TUMOR-DETECTOR.ipynb

2.Follow the steps in the notebook to:

 - Preprocess the data.

 - Train the CNN model.

 - Evaluate the model performance.

3.Visualize the results and predictions.

## Model Architecture
The CNN architecture includes:

- Convolutional layers with ReLU activation.
- Max pooling for dimensionality reduction.
- Fully connected layers for classification.
- Dropout for regularization.

## Results
Key Metrics:
- Accuracy: e.g., 95%
- Loss: e.g., 0.15

Confusion Matrix:
- Visualized to show true positives, false positives, true negatives, and false negatives.

## Visualization
- Feature maps from intermediate layers are displayed to understand what the model learns.
- Random augmented samples are shown to demonstrate the preprocessing pipeline.

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

- Fork the repository.
- Create a new branch:

git checkout -b feature-branch-name

- Commit your changes and push:

git push origin feature-branch-name

- Open a pull request.





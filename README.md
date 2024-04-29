
# Fashion Clothing Classification

Welcome to the Fashion Clothing Classification project repository. The main objective of this project is to classify different types of clothing items using image classification and the Fashion MNIST dataset.

## Introduction

The Fashion MNIST dataset consists of grayscale images with a dimension of 28x28 pixels. The photos are categorized into ten classes of fashion items, such as T-shirts, trousers, dresses, and more.

## Objectives

The objectives of this project are as follows:

- Implement a VGG16 model to extract features from clothing images.
- Apply PCA to reduce feature dimensions while preserving important information.
- Compare the performance of neural networks using PCA-transformed inputs against those without PCA.

## Methodology

The project methodology involves the following key steps:

1. **Data Acquisition:** Obtain the Fashion MNIST dataset containing 60,000 training and 10,000 test images of clothing items.

2. **Data Pre-Processing:** Pre-processing data involves resizing images to match VGG16 input requirements and normalizing pixel values to a range between 0 and 1, facilitating model training.

3. **Feature Extraction:** Use the VGG16 model to extract features from the clothing images.

4. **Dimensionality Reduction:** Apply Principal Component Analysis (PCA) to reduce the feature dimensions while preserving the vital information.

5. **Model Comparison:** Train neural networks with PCA-transformed features and without to evaluate classification accuracy.

6. **Model Evaluation:** Assess model performance using accuracy metrics.

## Repository Contents

- `notebooks/`: Jupyter Notebook with detailed analysis and model implementation.
- `presentation/`: Presentation slides summarizing key project findings.

## Contributors

- Abhishek Gambhir

Please feel free to contribute to this project by suggesting improvements, reporting issues, or submitting pull requests!

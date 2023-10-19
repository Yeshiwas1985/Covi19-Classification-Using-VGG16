# COVID-19 Chest X-ray Classification Using VGG16

This repository contains a deep learning project for classifying chest X-ray images into three categories: COVID-19, Normal, and Viral Pneumonia. The goal of this project is to aid in the early detection of COVID-19 using medical imaging.

## Dataset

The dataset used in this project is the "COVID-19 Image Dataset" obtained from Kaggle. It contains a total of 317 images, including 137 COVID-19 X-rays, and images from the Normal and Viral Pneumonia categories. The dataset is split into training and testing sets for model evaluation.

### Source
- Dataset: [COVID-19 Image Dataset](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database)

## Project Overview

The project consists of the following major components:

1. Data Preprocessing: The chest X-ray images are preprocessed, resized to a common dimension (500x500 pixels), and normalized for model input.

2. Model Building: The deep learning models, including VGG16, ResNet50, MobileNet, and EfficientNet, are constructed and fine-tuned for image classification.

3. Data Augmentation: Data augmentation techniques are applied to the training dataset to improve model robustness and generalization.

4. Training and Evaluation: The models are trained and evaluated on the test dataset. Model performance metrics are reported, including accuracy, loss, and confusion matrices.

5. Saving Models: Trained models are saved for future use.

## Model Training

The project involves training multiple models to classify chest X-ray images into three categories: COVID-19, Normal, and Viral Pneumonia. The models are trained using the training dataset and evaluated on the test dataset.

### Sample Code

To train the models, you can use the provided Python code. Here's a basic code structure to get you started:

```python
# Define the directory paths for training and testing data.
train_dir = "path/to/train_data/"
test_dir = "path/to/test_data/"

# Load, preprocess, and split the data.

# Define and compile the model.

# Train the model.

# Evaluate the model.

# Save the model.



# Where's Waldo? Detection using YOLOv5

## Project Overview

This project leverages the YOLOv5 deep learning model to automate the detection of Waldo in "Where's Waldo?" images. The model is trained on a custom dataset of annotated images and is capable of accurately identifying and localizing Waldo in complex and crowded scenes. The project demonstrates the potential of object detection models in solving intricate visual puzzles.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Training](#model-training)
- [Results](#results)
- [Installation](#installation)

## Dataset

The dataset consists of 943 "Where's Waldo?" images, each annotated with bounding boxes around Waldo. The images are split into training, validation, and testing sets.
     
- **Training Data**: Used to train the YOLOv5 model.
- **Validation Data**: Used to tune hyperparameters and prevent overfitting.
- **Test Data**: Used to evaluate the model's performance.
-  https://universe.roboflow.com/tan-rmi/whereiswaldo-ssmol/dataset/1
## Model Training

The YOLOv5 model was trained with the following settings:

- **Learning Rate**: 0.01
- **Confidence Threshold**: 0.75
- **Epochs**: Customizable based on dataset size and model performance.

The training process involves fine-tuning the model on the custom dataset until it achieves satisfactory accuracy in detecting Waldo.

## Results

The trained YOLOv5 model achieved an accuracy of approximately 80% on the test dataset. The results indicate the model's effectiveness in identifying Waldo across different challenging images. The model can be further optimized for better performance.

## Installation

To set up the project locally, follow these steps:

1. **Download the Dataset and Extract it**:
     https://universe.roboflow.com/tan-rmi/whereiswaldo-ssmol/dataset/1
2. **Follow the steps in ipynb file**:

3. **It's That easy**

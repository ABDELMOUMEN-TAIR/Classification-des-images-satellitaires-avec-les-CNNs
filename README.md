# Satellite Image Classification Using Deep Learning (CNN)

## Overview

This project focuses on employing Convolutional Neural Networks (CNNs) to classify satellite images, comparing a Classic CNN model with the EfficientNetV2 Model. Satellite imagery holds immense value across diverse fields such as agriculture, urban planning, disaster management, and environmental monitoring. Automating the classification of these images can yield valuable insights and facilitate informed decision-making processes.

## Dataset

The dataset utilized in this project, EuroSat, comprises satellite images paired with corresponding ground truth labels. Given the varied nature of satellite imagery, datasets may differ based on specific applications. It's essential to ensure proper organization and division of the dataset into training, validation, and test sets.

## Model Architecture

The convolutional neural network architecture employed in this project, featuring 5 convolutional layers and 5 max-pooling layers, is tailored to efficiently extract features from satellite images and categorize them into predefined classes.

The EfficientNetV2 Model has demonstrated state-of-the-art performance across various image classification benchmarks while maintaining high efficiency in terms of model size and computational cost. It serves as a robust architecture for tasks requiring lightweight yet accurate deep learning models.

## Training

The training process involves feeding satellite images into the CNN model and adjusting model parameters to minimize classification error. Experimentation with different hyperparameters and optimization techniques is recommended to achieve optimal performance.

## Evaluation

Trained models are evaluated using a separate set of test images to assess their performance and generalization ability, with metrics such as accuracy and F1-score.

## Results

The results of the satellite image classification model will be presented in terms of performance metrics and visualizations, offering insights into model effectiveness and potential applications.

- **Overall Accuracy**: The EfficientNetV2 model achieves significantly higher accuracy compared to the traditional CNN model, correctly classifying nearly 97% of samples in the test dataset, while the classic CNN model achieves an accuracy of approximately 81%.

- **F1 Score**: The F1 score, representing a balance between precision and recall, is also notably higher for the EfficientNetV2 model. It obtained an F1 score of 96.56%, indicating excellent precision and recall for each class. In contrast, the classic CNN model achieved an F1 score of 80.99%, reflecting lower performance in handling false positives and false negatives.

## The Results are in the ScreenShot Folder 

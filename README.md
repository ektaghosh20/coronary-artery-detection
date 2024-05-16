
# Coronary Artery Detection using Deep Learning Models

This project focuses on detecting coronary artery abnormalities using deep learning techniques. Six different Convolutional Neural Network (CNN) models are implemented and compared. The best-performing model, DenseNet201, is selected for further analysis.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models](#models)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Coronary artery disease (CAD) is a significant cause of morbidity and mortality globally. Early detection of coronary artery abnormalities can lead to better patient outcomes. This project utilizes deep learning models to automatically detect coronary artery abnormalities from medical images.

## Dataset

The dataset is divided into three splits: training, testing, and validation. Each split contains positive and negative folders:

- **Training**: Used to train the models.
- **Testing**: Used to evaluate the models' performance on unseen data.
- **Validation**: Used to fine-tune hyperparameters and prevent overfitting during training.

## Models

Six CNN models are implemented and compared:

1. DenseNet201
2. DenseNet121
3. GoogLeNet
4. ResNet50
5. VGG16
6. VGG19

## Evaluation Metrics

The following evaluation metrics are used to assess the models' performance:

- **F1 Score**: Harmonic mean of precision and recall.
- **Precision**: Ratio of true positive predictions to the total predicted positives.
- **Confusion Matrix**: Provides a summary of the model's performance.
- **Comparative Analysis**: Performance comparison among models based on the above metrics.

## Results

After training and evaluating the models, the DenseNet201 model demonstrates the best performance in terms of F1 score, precision, and overall accuracy. Detailed results and comparative analysis are provided in the project report.

## Usage

To use this project:

1. Clone the repository:

```bash
git clone https://github.com/ektaghosh20/coronary-artery-detection.git

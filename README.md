# Hand Gesture Recognition with Convolutional Neural Networks (CNN)

## Overview

This repository contains the code and resources for building a Hand Gesture Recognition model using Convolutional Neural Networks (CNNs). The model is trained on the LeapGestRecog dataset, capturing hand gesture images through Leap Motion sensors. The project covers data loading, preprocessing, CNN architecture definition, training, evaluation, and includes visualizations of training and validation accuracy/loss curves.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Visualization](#visualization)

## Installation

To run the notebook locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/dipeshbabu/PRODIGY_ML_04.git
   ```

````

2. Navigate to the project directory:

   ```bash
   cd PRODIGY_ML_04
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

- Open and run the Jupyter notebook `PRODIGY_ML_04.ipynb` to explore the code and execute each cell.

## Dataset

The dataset used in this project is the [LeapGestRecog](https://www.kaggle.com/gti-upm/leapgestrecog) dataset available on Kaggle. It contains images of hand gestures captured by Leap Motion sensors.

## Model Architecture

The CNN architecture used for Hand Gesture Recognition consists of multiple convolutional layers followed by max-pooling layers, flattening, and dense layers.

## Training

The model is trained using the TensorFlow and Keras libraries. The training process is detailed in the notebook with customizable hyperparameters.

## Evaluation

The model's performance is evaluated on a test set, and accuracy metrics are reported.

## Visualization

Training and validation accuracy/loss curves are visualized using Matplotlib to provide insights into the model's performance over epochs.
````

# Plant-Disease-Detection-Model-Deep-Learning-Mini-Project

This project involves building a model that uses RGB photos to forecast illnesses in crops. The dataset comprises two folders, Diseased and Healthy, which contain images of leaves with respective labels. The Diseased folder contains diseased/unhealthy images affected by Apple Scab, Black Rot, or Cedar Apple Rust.

## Table of Contents

- [Contributors](#contributors)
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Models](#models)
  - [Traditional Deep Learning Model](#traditional-deep-learning-model)
  - [Transfer Learning Model](#transfer-learning-model)
- [Comparison of Models](#comparison-of-models)
- [Results](#results)
- [License](#license)

## Contributors

- **2020/E/022**: Anuja Bandara.
- **2020/E/028**: Ruwan Pradeep.
- **2020/E/090**: Kishara Manilka.

## Project Overview

The goal of this project is to develop an automated system that can accurately classify plant leaves as healthy or diseased. Early detection of plant diseases can help in taking timely action to protect crops and increase agricultural productivity.

## Dataset

The dataset is divided into two main folders:
- **Diseased**: Contains images of leaves affected by Apple Scab, Black Rot, or Cedar Apple Rust.
- **Healthy**: Contains images of healthy leaves.

## Models

### Traditional Deep Learning Model

This model was built using basic deep learning techniques in TensorFlow. It includes several convolutional layers, max-pooling layers, and dense layers for classification.

### Transfer Learning Model

This model utilizes the Xception pre-trained model. Transfer learning involves using a pre-trained model as the starting point, which helps in achieving higher accuracy with less training data and time.

## Comparison of Models

| Metric               | Traditional Deep Learning Model | Transfer Learning Model |
|----------------------|---------------------------------|-------------------------|
| Training Time        | Higher                          | Lower                   |
| Number of Epochs     | More                            | Fewer                   |
| Accuracy             | Lower                           | Higher                  |
| Model Complexity     | High                            | Moderate                |

## Results

The transfer learning model achieved higher accuracy with fewer epochs and less training time compared to the traditional deep learning model.

## Installation

To run this project, you need to have Python and the following libraries installed:

- TensorFlow
- NumPy
- Matplotlib

## License
This project is licensed under the MIT License. See the LICENSE file for details.


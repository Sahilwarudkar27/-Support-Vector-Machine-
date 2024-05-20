# Handwritten Digit Classification Using SVM

## Project Overview

This project demonstrates the use of Support Vector Machine (SVM) to classify handwritten digits. Leveraging an online digits dataset, the goal is to accurately identify digit images based on their pixel values. This project showcases the practical application of machine learning in the field of image recognition.

## Table of Contents

- [Introduction](#introduction)

- [Dataset](#dataset)

- [Features](#features)

- [Methodology](#methodology)

- [Results](#results)

- [Usage](#usage)

- [Contributing](#contributing)

- [License](#license)

## Introduction

Handwritten digit classification is a common task in machine learning and computer vision. The objective is to create a model that can recognize and classify handwritten digits from 0 to 9. This project uses a Support Vector Machine (SVM) classifier to achieve this goal, providing a robust approach to image recognition.

## Dataset

The dataset used for this project is the famous digits dataset available from the sklearn library, which consists of 1,797 images of hand-written digits, each 8x8 pixels. Each image is represented by 64 features (pixel values), and the corresponding labels are the digit values from 0 to 9.

## Features

The key features of this project are:

- **Pixel Values**: Each digit image is represented by an 8x8 grid of pixel values, leading to 64 features per image.
- **Target Labels**: The corresponding digit (0-9) that each image represents.

## Methodology

1. **Data Preprocessing**:
    - Loaded the digits dataset from sklearn.
    - Split the dataset into training and test sets.

2. **Exploratory Data Analysis (EDA)**:
    - Visualized sample images from the dataset.
    - Analyzed the distribution of pixel values and target labels.

3. **Model Implementation**:
    - Implemented an SVM classifier using the `scikit-learn` library.
    - Trained the model on the training set.
    - Tuned hyperparameters using grid search and cross-validation.

4. **Model Evaluation**:
    - Evaluated the model’s performance using metrics such as accuracy, precision, recall, and F1-score.
    - Analyzed confusion matrix to understand the classification performance across different digits.

## Results

The SVM model achieved the following performance metrics on the test set:
- **Accuracy**: 98.61%
- **Precision**: 99.00%
- **Recall**: 99.00%
- **F1-score**: 99.00%

These results indicate that the SVM classifier provides a high level of accuracy in predicting handwritten digits.

## Visualization

![image](https://github.com/Sahilwarudkar27/-Support-Vector-Machine-/assets/99885674/7dc38ce9-1b8f-4e3c-a3cc-6fd7aa6de7dc)

### Sample Output
![image](https://github.com/Sahilwarudkar27/-Support-Vector-Machine-/assets/99885674/c7c7a851-f2d8-461b-b0a9-a9c383f2f967)

## Usage

To use this project, follow these steps:

1\. **Access the Kaggle notebook**:

   - Open the Kaggle notebook by clicking on the following link: [[Link to Kaggle notebook](https://www.kaggle.com/code/sahilwarudkar/handwritten-digit-classification/edit)]

2\. **Run the notebook**:

   - Once the notebook is open, you can run each cell sequentially to see the analysis and model implementation.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


# Chronic Kidney Disease Prediction

This project aims to predict Chronic Kidney Disease (CKD) using machine learning techniques. The prediction is based on the "Chronic_kidney" dataset.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Chronic Kidney Disease is a serious health condition that affects the kidneys' ability to function properly. Early detection and prediction of CKD can significantly improve patient outcomes. This project utilizes machine learning algorithms to predict CKD based on various clinical features.

## Dataset

The dataset used in this project is called "Chronic_kidney." It contains information about patients, including demographic data, laboratory test results, and medical history. The dataset is used to train and evaluate the machine learning models for CKD prediction.  <br><br>
<a href=https://ieee-dataport.org/documents/chronic-kidney-disease-data-set#files> Dataset download link</a>

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```
   git clone https://github.com/your-username/chronic-kidney-disease-prediction.git
   ```

2. Install the required dependencies:

   ````
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:

   ````
   jupyter notebook main.ipynb
   ```

## Usage

The Jupyter notebook file `main.ipynb` contains the code implementation for CKD prediction. Open the notebook using Jupyter and follow the instructions provided to explore the dataset, preprocess the data, train different machine learning models, and evaluate their performance.

## Models

The following machine learning models are implemented in this project:

- Linear Regression
- Lasso Regression
- Logistic Regression
- Decision Tree Classifier
- Gaussian Naive Bayes
- Random Forest Classifier
- XGBoost

Feel free to experiment with different models and parameters to improve the prediction accuracy.

## Evaluation

The performance of the machine learning models is evaluated using the following metrics:

- Confusion Matrix
- Accuracy Score

These metrics provide insights into the model's ability to correctly classify patients as having CKD or not.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

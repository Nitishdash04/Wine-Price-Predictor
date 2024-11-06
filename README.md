# Wine Quality Prediction

This repository contains a machine learning project aimed at predicting the quality of wine based on various physicochemical properties. Using a dataset of wine samples, this model seeks to classify the quality of wine as high or low, helping winemakers and quality assurance teams in the wine industry make data-driven decisions.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling Process](#modeling-process)
- [Evaluation](#evaluation)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Overview

Wine quality is influenced by several chemical characteristics such as acidity, sugar content, pH, and alcohol concentration. This project applies supervised learning techniques to predict the quality of wine, providing insights into the role each feature plays in determining quality.

## Dataset

The dataset used in this project comes from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality), containing data on red and white wines from Portugal's Vinho Verde region.

- **Attributes:** 11 physicochemical features
- **Target Variable:** Wine quality score (ranges from 0 to 10)

## Features

The dataset includes the following features:
- **Fixed acidity**
- **Volatile acidity**
- **Citric acid**
- **Residual sugar**
- **Chlorides**
- **Free sulfur dioxide**
- **Total sulfur dioxide**
- **Density**
- **pH**
- **Sulphates**
- **Alcohol**

The target variable is the **quality** score, which we simplify into binary classes (high-quality vs. low-quality).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/wine-quality-prediction.git
   cd wine-quality-prediction
   ```
2. Install the necessary packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Open and run the Jupyter Notebook (`Wine_Quality_Prediction.ipynb`) to go through the data exploration, preprocessing, and modeling steps.
2. To train the model and make predictions directly from the command line:
   ```bash
   python wine_quality_prediction.py
   ```

## Modeling Process

1. **Data Preprocessing:** Handle missing values, encode categorical variables, and normalize numerical features.
2. **Feature Engineering:** Analyze and select the most relevant features.
3. **Model Selection:** Use multiple classifiers (e.g., Decision Trees, Random Forests, SVM, etc.) and optimize hyperparameters to achieve the best performance.
4. **Training and Testing:** Split the data into training and testing sets, and evaluate model accuracy, precision, recall, and F1 score.

## Evaluation

The models are evaluated based on metrics such as:
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**

## Results

The Random Forest model performed best with an accuracy of **X%** and an F1 score of **Y%** on the test set, making it our preferred model for wine quality prediction.

## Technologies Used

- Python (pandas, NumPy, scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Git

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for improvements.

## Linkedin
[Linkedin](https://www.linkedin.com/in/nitish-kr-dash/)

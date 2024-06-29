
# Wine Quality Predictor using Random Forest Classifier

This project builds a machine learning model to predict wine quality using its chemical properties. It explores a publicly available wine dataset, trains a Random Forest model, and analyzes the factors influencing quality through data visualization. The project aims to provide a tool for winemakers, distributors, and enthusiasts to better understand and predict wine quality.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Overview](#project-overview)
- [Data Analysis and Visualization](#data-analysis-and-visualization)
- [Preprocessing](#preprocessing)
- [Training and Testing](#training-and-testing)
- [Results](#results)


## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/Wine_Quality_Predictor.git
    cd Wine_Quality_Predictor
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the notebook, use the following command:
```bash
jupyter notebook Wine_Quality_Predictor.ipynb
```

Follow the cells in the notebook to perform the analysis and prediction.

## Project Overview

The project involves the following steps:

1. **Importing Dependencies:** Load necessary libraries.
2. **Data Analysis and Visualization:** Perform exploratory data analysis (EDA) to understand the dataset.
3. **Preprocessing:** Prepare the data for training.
4. **Training and Testing:** Train the model and evaluate its performance.

## Data Analysis and Visualization

Performed EDA to understand the distribution and relationships in the data. Visualizations include:
- Distribution of wine quality
- Relationships between wine quality and various features (volatile acidity, citric acid, residual sugar, etc.)
- Correlation heatmap to identify feature relationships

## Preprocessing

Data preprocessing steps include:
- Splitting the dataset into features (X) and labels (Y)
- Binarizing the quality labels (good quality if >=7, otherwise bad quality)
- Splitting the data into training and testing sets

## Training and Testing

Trained a RandomForestClassifier and evaluated its performance on both the training and testing sets. The steps include:
- Training the model
- Evaluating training accuracy
- Evaluating testing accuracy
- Making predictions on new data

## Results

- The model's training accuracy
- The model's testing accuracy
- Predicting the quality of a new wine sample based on its features


---

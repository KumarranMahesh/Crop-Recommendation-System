# Crop Recommendation System

This project aims to build a machine learning model that can recommend the most suitable crop to grow based on various environmental and soil parameters. The model is trained on a dataset containing information about different crops and their respective growing conditions.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)

## Overview
The Crop Recommendation System leverages machine learning algorithms to suggest the most appropriate crop to cultivate under given conditions. It includes data preprocessing, exploratory data analysis (EDA), model training, and evaluation steps to ensure high accuracy and reliability.

## Dataset
The dataset used for this project is `Crop_recommendation.csv`, which contains the following columns:
- N: Ratio of Nitrogen content in soil
- P: Ratio of Phosphorous content in soil
- K: Ratio of Potassium content in soil
- temperature: Temperature in degree Celsius
- humidity: Relative humidity in %
- ph: pH value of the soil
- rainfall: Rainfall in mm
- label: Type of crop

## Installation
To run this project, you need to have Python installed along with several libraries. You can install the required libraries using the following command:
```bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/KumarranMahesh/Crop-Recommendation-System.git
```

2. Navigate to the project directory:
```bash
cd crop-recommendation-system
```

3. Ensure you have the dataset Crop_recommendation.csv in the data directory.

4. Run the Jupyter notebook or Python script to execute the project.

## Model Training
The project includes the following steps for model training:

1. **Data Preprocessing**: Handling missing values, scaling numerical features, and encoding categorical features.
2.** Exploratory Data Analysis (EDA)**: Visualizing distributions and correlations of features using Matplotlib and Seaborn.
3. **Model Implementation**: Training multiple machine learning models including Logistic Regression, Random Forest, Gradient Boosting, and more.

## Evaluation
The models are evaluated based on accuracy, with a split of the dataset into training and testing sets using an 80-20 ratio. The Random Forest model achieved the highest accuracy of 100%.

## Results
- Random Forest Model: Achieved an accuracy of 100% on the test set.
- The trained model is saved as model.pkl for future use.

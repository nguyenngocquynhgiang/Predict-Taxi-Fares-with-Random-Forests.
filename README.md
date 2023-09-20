
# Predict Taxi Fares with Random Forests

This project is an exploration of predicting taxi fares using the Random Forest machine learning algorithm. We aim to build a predictive model that can estimate taxi fares based on various features like distance, time, and location using a dataset of 49,999 New York taxi trips from 2013.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)


## Overview

The New York taxi industry is lucrative, and understanding the factors that influence taxi fares can benefit both taxi drivers and passengers. In this project, we leverage machine learning to predict taxi fares using Random Forests. We explore the dataset, clean the data, and build a predictive model that considers various factors to estimate taxi fares.

## Dataset

We use a dataset consisting of 49,999 New York taxi trips from 2013. The dataset includes information such as pickup datetime, longitude, latitude, trip duration, fare amount, and tip amount. This data serves as the foundation for our predictive model.

## Installation

To run this project locally, you will need to have the following dependencies installed:

- Python (3.x recommended)
- Jupyter Notebook
- scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn



## Usage

The project is organized into Jupyter Notebooks, making it easy to follow the analysis step-by-step. Here's how to use the project:

1. Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/Predict-Taxi-Fares-with-Random-Forests.git
```

2. Navigate to the project directory:

```bash
cd Predict-Taxi-Fares-with-Random-Forests
```

3. Open the Jupyter Notebooks to explore and run the analysis:

- `1_Exploratory_Data_Analysis.ipynb`: Explore the dataset and perform initial data analysis.
- `2_Data_Preprocessing_and_Modeling.ipynb`: Clean the data, preprocess features, and build the Random Forest model.
- `3_Model_Evaluation.ipynb`: Evaluate the model's performance using various metrics.

## Model Training

We use the Random Forest algorithm to build a predictive model. The model takes into account factors like latitude, longitude, time, and day of the week to estimate taxi fares.

## Evaluation

The model's performance is evaluated using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R2) score. These metrics provide insights into the accuracy of our fare predictions.

## Results

Our analysis and model building process have resulted in a predictive model for taxi fares. We present the model's findings and insights in the Jupyter Notebooks. The model's performance metrics are also discussed, allowing for a clear understanding of its accuracy.

contribution guidelines](CONTRIBUTING.md).


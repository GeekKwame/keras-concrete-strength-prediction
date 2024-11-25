
# Concrete Strength Prediction with Neural Networks

This project implements a neural network using Keras to predict the compressive strength of concrete based on its ingredients.

## Project Overview

- **Objective**: Predict concrete strength using a dataset of material properties.
- **Dataset**: The dataset includes cement, slag, fly ash, water, superplasticizer, coarse aggregate, fine aggregate, and the age of concrete samples.

## Dataset

The dataset used in this project is sourced from [Cognitive Class](https://cognitiveclass.ai/). It contains the following columns:
- Cement
- Blast Furnace Slag
- Fly Ash
- Water
- Superplasticizer
- Coarse Aggregate
- Fine Aggregate
- Age (days)
- Compressive Strength

## Model Details

The model is a feedforward neural network built using the Keras library with the following features:
- Input layer matching the number of predictors.
- One hidden layer with ReLU activation.
- Output layer predicting the target variable (compressive strength).

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/GeekKwame/keras-concrete-strength-prediction
   ```

2. Navigate to the project directory and run the notebook using Jupyter:
   ```bash
   jupyter notebook Model_with_Keras.ipynb
   ```

## Example Outputs

The project calculates the Mean Squared Error (MSE) between predicted and actual values over multiple runs to evaluate model stability and performance.


# house-price-prediction
House price prediction using neural networks and hyperparameter optimization.


# House Price Prediction Using Neural Networks

## Project Overview

This project develops and evaluates neural network models to predict residential house prices using structured housing data.

Three approaches are compared:
- Baseline Neural Network
- Regularized Neural Network
- Hyperparameter-Optimized Neural Network

## Objectives

- Explore and preprocess housing data.
- Handle missing values and encode categorical variables.
- Develop neural network regression models using TensorFlow and Keras.
- Apply regularization techniques to reduce overfitting.
- Optimize model hyperparameters using Keras Tuner.
- Compare predictive performance using MAE, RMSE, and R-squared.

## Methodology

1. Data loading and exploratory data analysis
2. Missing-value treatment and feature encoding
3. Training and validation split
4. Feature scaling
5. Baseline model development
6. Regularized model development
7. Hyperparameter optimization using Random Search
8. Model evaluation and comparison

## Models

### Baseline Neural Network
A fully connected neural network used as the initial benchmark.

### Regularized Neural Network
A neural network incorporating dropout to help reduce overfitting.

### Optimized Neural Network
A neural network with hyperparameters selected using Keras Tuner.

## Evaluation Metrics

- **MAE:** Mean Absolute Error
- **RMSE:** Root Mean Squared Error
- **R-squared:** Proportion of variance explained by the model

## Results

The optimized neural network achieved the best predictive performance
among the three evaluated models.

| Model | MAE | RMSE | R-squared |
|---|---:|---:|---:|
| Optimized Neural Network | 22,562.29 | 35,632.88 | 0.8345 |
| Baseline Neural Network | 24,288.17 | 38,406.54 | 0.8077 |
| Regularized Neural Network | 28,697.75 | 44,389.30 | 0.7431 |

The optimized neural network achieved the lowest MAE and RMSE and
the highest R-squared, indicating the strongest predictive performance
on the validation set.

The best-performing model will be identified based on validation performance, with lower MAE and RMSE and higher R-squared indicating better predictive accuracy.

## Technologies

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- TensorFlow and Keras
- Keras Tuner
- Jupyter Notebook

## Dataset

House prices dataset obtained from Kaggle.

Dataset source: https://www.kaggle.com/datasets/lespin/house-prices-dataset

## Reproducibility

Install the required dependencies and run the notebook sequentially.

```bash
pip install -r requirements.txt
pandas
numpy
matplotlib
seaborn
scikit-learn
tensorflow
keras-tuner
tensorboard
kagglehub
jupyter
```

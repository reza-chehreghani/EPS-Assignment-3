# Engineering Probability and Statistics Assignment 3

This repository contains my solutions for **Engineering Probability and Statistics Assignment 3**, which focuses on **Mean Squared Error (MSE)**, **Regression Analysis**, and **Central Limit Theorem (CLT) with Sampling**. Below is a detailed explanation of each part and the corresponding solutions.

## 1. Mean Squared Error (MSE) and Autoencoders

This part involves working with **Autoencoders** to reconstruct images from the MNIST dataset and calculating the **Mean Squared Error (MSE)** between the original and reconstructed images. The tasks include:
- **Loading and Preprocessing Data**: Loading the MNIST dataset and preprocessing the images.
- **Reconstructing Images**: Using a pre-trained autoencoder model to reconstruct images.
- **Calculating MSE**: Implementing a function to calculate the MSE between original and reconstructed images.
- **Hypothesis Testing**: Using the **Kolmogorov-Smirnov test** to check if the MSE values follow a normal distribution.

### Approach:
- **Autoencoder**: Loaded a pre-trained autoencoder model to reconstruct MNIST images.
- **MSE Calculation**: Implemented a custom function to calculate MSE without using built-in libraries.
- **Statistical Analysis**: Used the Kolmogorov-Smirnov test to analyze the distribution of MSE values.

## 2. Regression Analysis and Least Squares

This part focuses on **Linear Regression** and the impact of **outliers** and **high-leverage points** on regression models. The tasks include:
- **Understanding Outliers and Leverage Points**: Researching the effects of outliers and high-leverage points on regression models.
- **Implementing Linear Regression**: Implementing linear regression using the **Least Squares** method.
- **Comparing Regression Models**: Comparing regression models with and without outliers/leverage points.
- **Proposing Better Models**: Suggesting alternative regression models to handle outliers and leverage points.

### Approach:
- **Regression Implementation**: Implemented linear regression from scratch using the Least Squares method.
- **Visualization**: Plotted regression lines and calculated the **Coefficient of Determination (R²)** for each model.
- **Model Improvement**: Suggested robust regression techniques to handle outliers and leverage points.

## 3. Central Limit Theorem (CLT) and Sampling

This part explores the **Central Limit Theorem (CLT)** and its application to sampling. The tasks include:
- **Data Preprocessing**: Handling missing values in the FIFA 2020 dataset and replacing them with appropriate values.
- **Descriptive Statistics**: Calculating and visualizing descriptive statistics (min, Q1, Q2, Q3, max) for the `age` variable.
- **Sampling and CLT**: Sampling from the `weight` variable and analyzing the distribution of sample means.
- **Q-Q Plots and Hypothesis Testing**: Using Q-Q plots and the **Shapiro-Wilk test** to compare distributions and test for normality.
- **Poisson Distribution**: Sampling from the Poisson distribution and comparing it with the normal distribution.

### Approach:
- **Data Cleaning**: Replaced missing values in the FIFA dataset using appropriate methods.
- **Sampling**: Sampled from the `weight` variable and analyzed the distribution of sample means.
- **Statistical Tests**: Used Q-Q plots and the Shapiro-Wilk test to compare distributions and test for normality.
- **Poisson Distribution**: Generated samples from a Poisson distribution and compared them with a normal distribution.

## Code Structure
The repository contains separate Jupyter Notebooks for each part:
- **Autoencoder and MSE**: Implementation of autoencoder-based image reconstruction and MSE calculation.
- **Regression Analysis**: Implementation of linear regression and analysis of outliers/leverage points.
- **CLT and Sampling**: Analysis of the Central Limit Theorem and sampling techniques, including Poisson distribution.

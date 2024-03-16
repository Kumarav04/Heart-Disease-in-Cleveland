README.md

# Heart Disease Classification Project

## Introduction
This project aims to develop machine learning classification models to predict the presence or absence of coronary artery disease (CAD) based on various demographic and medical factors. The dataset used for this analysis contains information on patients' age, sex, medical history, and other relevant parameters.

## Methods Used
- **Data Cleaning and Wrangling:** The dataset was cleaned and preprocessed to remove missing values, convert variables to the correct data types, and balance the distribution of CAD diagnoses. The data was split into training and testing sets for model evaluation.
- **Exploratory Data Analysis (EDA):** Summary statistics were calculated for each variable, and histograms were created to visualize the distribution of observations in each predictor.
- **Classification Models:** Three types of classification models were developed: one using only demographic data (census data), one using only medical data, and one incorporating both types of predictors. The k-nearest neighbors (KNN) algorithm was used for classification, and the optimal value of k was determined through cross-validation.
- **Evaluation Metrics:** Model accuracy, false positive rate, and false negative rate were calculated to evaluate the performance of each model.

## Technology Used
- **Programming Language:** R
- **Libraries:** tidyverse, caret, kknn
- **Tools:** RStudio, ggplot2 for data visualization

## Project Structure
- **Data:** The dataset used for analysis.
- **HTML File** Containing all the code and results of our analysis.
- **README.md:** This file providing an overview of the project.


## Acknowledgements
The dataset used in this project is sourced from the UCI Machine Learning Repository. Special thanks to the contributors of this dataset for making it publicly available for research purposes.

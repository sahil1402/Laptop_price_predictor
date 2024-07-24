# Laptop Price Prediction

This project focuses on predicting laptop prices using machine learning techniques. The dataset includes various features of laptops, such as brand, processor specifications, RAM, storage, OS, and more.
Web-based application that predicts the price of the laptop according to the configuration input by user.
The project includes eight major stages of the ML life cycle to result in structured, practical business value.

## Project Overview

The goal of this project is to build a model that accurately predicts the price of a laptop based on its features.

## Table of Contents

- Dataset
- Installation
- Data Preprocessing
- Feature Engineering
- Model Evaluation
- Hyperparameter Tuning
- Results
- Technologies Used
- Visualizations
- Conclusion

# Business Problem
Predict the Price of laptop on the basis of

Context A dataset for 1300 laptop models.
Content, Company Name, Product Name, Laptop Type, Screen Inches, Screen Resolution, CPU Model, RAM Characteristics, Memory, GPU Characteristics, Operating System, Laptop's Weight, Laptop's Price
Source-https://www.kaggle.com/ionaskel/laptop-prices

## Dataset

The dataset contains 823 entries with the following columns:
- `brand`
- `processor_brand`
- `processor_name`
- `processor_gnrtn`
- `ram_gb`
- `ram_type`
- `ssd`
- `hdd`
- `os`
- `os_bit`
- `graphic_card_gb`
- `weight`
- `warranty`
- `Touchscreen`
- `msoffice`
- `Price`
- `rating`
- `Number of Ratings`
- `Number of Reviews`

## Installation

To run this project, you will need to have Python installed along with the following libraries:
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib

You can install these libraries using pip:

```bash
pip install pandas numpy scikit-learn seaborn matplotlib
```

## Data Preprocessing

- **Loaded the dataset** and checked for datatypes, null values, and duplicates.
- **Dropped unnecessary columns** and labeled categorical columns.

## Feature Engineering

Selected the following features for prediction:
- `brand`
- `processor_brand`
- `processor_name`
- `processor_gnrtn`
- `ram_gb`
- `ram_type`
- `ssd`
- `hdd`
- `os`
- `os_bit`
- `graphic_card_gb`
- `weight`
- `warranty`
- `Touchscreen`
- `msoffice`
- `rating`

## Model Evaluation

Evaluated the following models:
- Linear Regression
- Decision Tree
- Random Forest

## Hyperparameter Tuning

Used **RandomizedSearchCV** for hyperparameter tuning of the RandomForestRegressor to achieve the best performance.


## Technologies Used

- **Python:** For data processing and model building.
- **Pandas & NumPy:** For data manipulation.
- **Scikit-Learn:** For machine learning algorithms.
- **Seaborn & Matplotlib:** For data visualization.

Performance Metric

1. R2 Score

2. Mean Absolute Error

# Display
<img width="407" alt="1" src="https://user-images.githubusercontent.com/63099028/183035027-a8e3e365-7d37-4ed1-93d3-02ecd44ff668.PNG">


# Results Comparision
# Amazon Price

<img width="597" alt="1" src="https://user-images.githubusercontent.com/63099028/180611808-28a90158-4f95-4199-b767-f53e584b7366.PNG">

# Predicted Price

<img width="938" alt="2" src="https://user-images.githubusercontent.com/63099028/180611810-97d7b279-f1b0-4f62-9469-4f01b931e1f6.PNG">

## Results

The Random Forest model provided the best performance with optimal hyperparameters, effectively predicting laptop prices based on the given features.

## Visualizations

Visualized the model's accuracy using scatter and regression plots.

## Conclusion

The project successfully built a model to predict laptop prices with high accuracy using Random Forest with hyperparameter tuning.

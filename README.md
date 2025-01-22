# Home Price Prediction

## Overview
This project demonstrates the use of linear regression to predict house prices based on their area. The dataset contains information about house areas (in square feet) and their respective prices. The project utilizes Python and its powerful libraries for data manipulation, visualization, and machine learning.

## Features
- Scatter plot visualization to show the relationship between area and price.
- Training a linear regression model using the `sklearn` library.
- Predicting house prices for a given area.
- Calculation of model coefficients and intercept.

## Dataset
The dataset (`homeprices.csv`) includes:
- **Area**: The size of the house in square feet.
- **Price**: The price of the house.

### Example Data
| Area (sq ft) | Price (Rs) |
|--------------|------------|
| 2600         | 550,000    |
| 3000         | 565,000    |
| 3200         | 610,000    |
| 3600         | 680,000    |
| 4000         | 725,000    |

## Steps
### 1. Data Loading and Visualization
- Load the dataset using pandas.
- Plot a scatter plot to visualize the relationship between `area` and `price`.

### 2. Model Training
- Prepare the feature (`area`) and target (`price`) columns.
- Train a linear regression model using `LinearRegression` from `sklearn`.

### 3. Prediction
- Predict house prices for a given area.

### 4. Model Insights
- **Coefficient**: The increase in price per unit increase in area.
- **Intercept**: The base price of a house with an area of 0.

## Results
- **Predicted Price for 3300 sq ft**: Rs 628,715.75
- **Model Coefficient**: Rs 135.79 per sq ft
- **Model Intercept**: Rs 180,616.44

## Tools and Libraries
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For visualization.
- **Scikit-learn**: For linear regression modeling.

## Usage
1. Place the `homeprices.csv` file in the project directory.
2. Run the script to train the model and make predictions.

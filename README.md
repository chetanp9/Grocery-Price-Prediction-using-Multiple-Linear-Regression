## Grocery Price Prediction using Multiple Linear Regression ##
This repository contains a Jupyter Notebook that demonstrates how to predict grocery prices using a multiple linear regression model. The project uses a dataset containing various features related to grocery items, such as location, market, commodity type, and price ranges.

## Overview
The goal of this project is to build a predictive model that can estimate the price of grocery items based on certain features. The model is trained using multiple linear regression, a statistical method that models the relationship between a dependent variable and multiple independent variables.

## Dataset
The dataset used in this project includes the following features:

- State: The state in which the market is located.
- District: The district in which the market is located.
- Market: The specific market where the data was collected.
- Commodity: The type of grocery item.
- Variety: The variety of the commodity.
- Grade: The quality grade of the commodity.
- Min Price: The minimum price of the commodity.
- Max Price: The maximum price of the commodity.
- Modal Price: The most frequently occurring price.

## Preprocessing
Before training the model, the data is preprocessed to ensure it is in the correct format. This includes scaling the numerical features to ensure that all features contribute equally to the model.

 ## Model
The project uses a multiple linear regression model to predict the price of grocery items. The model is trained using the preprocessed data and is capable of making predictions based on new input data.

## Example Prediction
An example prediction made by the model is as follows:

## Input Features:
- Grocery:tomato
- Variety: Local
- Grade: FAQ
- Min Price: 640
- Max Price: 2160
- Predicted Price: 1357.00

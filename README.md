
# US Real estate price prediction project

## Dataset Overview
This repository contains a dataset and code for predicting real estate prices using machine learning models. The dataset is sourced from Kaggle and includes a variety of features related to real estate listings.

## Dataset Description
The dataset consists of a single CSV file: realtor-data.csv. It contains 2,226,382 entries with the following columns:

brokered_by: Categorical feature representing the agency or broker.
status: Housing status (e.g., ready for sale or ready to build).
price: Housing price, which may be the current listing price or a recently sold price.
bed: Number of beds in the property.
bath: Number of bathrooms in the property.
acre_lot: Property or land size in acres.
street: Categorical feature representing the street address.
city: City name where the property is located.
state: State name where the property is located.
zip_code: Postal code of the area.
house_size: Area or size of the house in square feet.
prev_sold_date: Date when the property was last sold.
Source
The dataset is available at: Kaggle - USA Real Estate Dataset

## Project Overview
This project involves building predictive models to estimate real estate prices. The following models have been implemented:

Linear Regression: A statistical method to model the relationship between the dependent variable (price) and one or more independent variables (features).
Random Forest: An ensemble learning method that constructs multiple decision trees and merges them to improve accuracy and control over-fitting.
Code
The provided code demonstrates the implementation of the above models. It includes data preprocessing, feature encoding, model training, and evaluation.

## Usage
Clone this repository.
Download the dataset from Kaggle and place the realtor-data.csv file in the project directory.
Run the provided code to train and evaluate the models.
License
This project is licensed under the MIT License - see the LICENSE file for details.



## Acknowledgements

Kaggle - USA Real Estate Dataset for providing the dataset.
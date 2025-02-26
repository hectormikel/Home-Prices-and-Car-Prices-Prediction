# Home-Prices-and-Car-Prices-Prediction

This repository contains code for predicting home prices and car prices using linear regression models. The code is written in Python and utilizes libraries such as Pandas, Polars, and Scikit-learn.

## Overview

The project includes two main tasks:

Predicting home prices based on the town and area.
Predicting car prices based on the car model, mileage, and age.


## Datasets

homeprices_dummy.csv: Contains data on home prices with features such as town and area.
carprices.csv: Contains data on car prices with features such as car model, mileage, and age.

## Dependencies

pandas: For data manipulation and analysis.
polars: For fast DataFrame operations.
scikit-learn: For machine learning algorithms and tools.


## Code Explanation

### Home Prices Prediction

Data Loading: The home prices dataset is loaded using Polars.
Data Preprocessing:
One-hot encoding is applied to the 'town' feature.
The original 'town' column and one of the dummy columns are dropped to avoid multicollinearity.
Model Training: A linear regression model is trained on the preprocessed data.
Prediction: The model is used to predict home prices for given inputs.
Evaluation: The model's performance is evaluated using the score method.


### Car Prices Prediction

Data Loading: The car prices dataset is loaded using Polars.
Data Preprocessing:
One-hot encoding is applied to the 'Car Model' feature.
The original 'Car Model' column and one of the dummy columns are dropped to avoid multicollinearity.
Model Training: A linear regression model is trained on the preprocessed data.
Prediction: The model is used to predict car prices for given inputs.
Evaluation: The model's performance is evaluated using the score method.

## Usage

To use the code, ensure you have the required libraries installed. You can install them using pip:

Copy
pip install pandas polars scikit-learn
Run the code in a Jupyter notebook or any Python environment that supports these libraries.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the GNU License. See the LICENSE file for details.

This README provides an overview of the project, explains the code, and includes instructions for usage and contributing.

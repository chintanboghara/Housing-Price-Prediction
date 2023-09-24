## Housing Price Prediction

## Overview

This project is a simple machine learning task that aims to predict median house prices based on median income. It uses a linear regression model for prediction and includes data preprocessing, visualization, model building, and evaluation.

## Project Structure

The project is organized as follows:

- **`housing.csv`**: This CSV file contains the dataset used for this project, including features like median income and median house value.

- **`housing_price_prediction.ipynb`**: This Jupyter Notebook contains the Python code for data analysis, preprocessing, modeling, and visualization.

## Prerequisites

Before running the code in this project, make sure you have the following dependencies installed:

- Python 3.x
- Jupyter Notebook
- Pandas
- Matplotlib
- Scikit-Learn

You can install these packages using pip:

```bash
pip install pandas matplotlib scikit-learn
```

## Usage

1. Clone this repository to your local machine:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd housing-price-prediction
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook housing_price_prediction.ipynb
   ```

4. Follow the instructions and comments in the Jupyter Notebook to execute the code step by step.

## Data

The dataset used in this project, `housing.csv`, contains the following columns:

- `median_income`: Median income of households in a particular area.
- `median_house_value`: Median house value for houses in a particular area.
- `total_bedrooms`: Total number of bedrooms in houses in a particular area.

## Results

The project will generate various visualizations and provide the R-squared score as a measure of the model's performance.

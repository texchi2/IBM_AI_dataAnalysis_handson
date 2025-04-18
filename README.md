# IBM AI Data Analysis Hands-on

This repository contains a data analysis project for predicting used car prices. The project uses machine learning techniques to analyze Ford vehicle sales data and build a predictive model for optimal pricing.

## Project Overview

The project includes:

- Exploratory Data Analysis (EDA) of used car sales data
- Data preprocessing and feature engineering
- Building and training predictive models for car prices
- Model evaluation and optimization
- Visualization of key insights and model performance

## Files

- `car_sales.qmd`: The main Quarto document containing the analysis and model
- `figures/`: Directory containing all generated visualizations
- `cleaned_car_data.csv`: Cleaned dataset (not included in repository)
- `augmented_car_data.csv`: Augmented dataset with synthetic samples (not included in repository)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Getting Started

1. Clone the repository
2. Install the required dependencies
3. Run the `car_sales.qmd` file using Quarto

## Results

The model achieved an R² score of 0.9346 on the test dataset, indicating that it explains approximately 93.46% of the variance in car prices. The Root Mean Squared Error (RMSE) is £2,983.69, meaning predictions typically deviate from actual prices by about £3,000.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

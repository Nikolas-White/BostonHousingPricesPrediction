# Predicting Housing Prices in Boston

## Project Overview

This project aims to predict the housing prices in the Boston area using supervised machine learning techniques. The dataset used is the Boston Housing dataset, which contains various features related to the socio-economic, environmental, and structural aspects of houses in different areas of Boston.

## Dataset

The dataset used for this project is the Boston Housing dataset, which includes the following features:
- CRIM: Per capita crime rate by town.
- ZN: Proportion of residential land zoned for lots over 25,000 sq. ft.
- INDUS: Proportion of non-retail business acres per town.
- CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise).
- NOX: Nitric oxides concentration (parts per 10 million).
- RM: Average number of rooms per dwelling.
- AGE: Proportion of owner-occupied units built prior to 1940.
- DIS: Weighted distances to five Boston employment centers.
- RAD: Index of accessibility to radial highways.
- TAX: Full-value property tax rate per $10,000.
- PTRATIO: Pupil-teacher ratio by town.
- B: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents by town.
- LSTAT: Percentage of lower status of the population.
- MEDV: Median value of owner-occupied homes in $1000s.

## Key Takeaways

- **Socio-Economic Status**: The low status population is the most influential factor in predicting house prices. Areas with higher proportions of low socio-economic status populations tend to have lower house prices.
- **Home Size and Features**: The average number of rooms per dwelling is positively correlated with house prices. Larger homes with more rooms are generally more valuable.
- **Environmental Quality**: Higher levels of nitric oxides concentration are associated with lower house prices.
- **Education Quality**: Lower pupil-teacher ratios (indicating better education quality) are associated with higher house prices.
- **Crime and Safety**: Higher crime rates negatively affect house prices.
- **Accessibility and Transportation**: Properties closer to employment centers and with better highway access are more desirable.
- **Property Taxes**: Higher property tax rates generally have a negative impact on house prices, but their effect can vary based on other factors.

## Requirements

- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib
- shap

## Usage

1. Clone the repository.
2. Install the required packages.
3. Run the Jupyter Notebook to follow the analysis and model building steps.
4. Use the generated SHAP summary plot to interpret the model predictions.

## Acknowledgements

This project uses data from the UCI Machine Learning Repository. 
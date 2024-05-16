# Linear-Regression-Analysis-of-Boston-Housing-Data

## Overview
This project explores the application of linear regression techniques to understand the dynamics of the housing market using the Boston dataset. The analysis covers both simple and multiple linear regression models to investigate the relationships between house prices and various predictors such as proximity to employment centers and room numbers.

## Data Source
The Boston dataset is used for this analysis, which is included in the `ISLP` library.

## Getting Started

### Prerequisites
Ensure you have Python installed along with the following libraries:
- numpy
- pandas
- seaborn
- matplotlib
- statsmodels
- scikit-learn

### Installation
To install the required Python libraries, you can use the following pip command:

```bash
pip install numpy pandas seaborn matplotlib statsmodels scikit-learn
```

### Load Data
The dataset can be loaded using the load_data function from the ISLP package:
```bash
from ISLP import load_data
Boston = load_data('Boston')
```

## Simple Linear Regression
Simple linear regression is used to explore the relationship between the median value of owner-occupied homes (medv) and the weighted distances to five Boston employment centres (dis). The analysis includes plotting, fitting the model, and hypothesis testing.


## Multiple Linear Regression
The multiple regression model includes additional predictors such as the number of rooms (rm). This section explores the effect of multiple factors on house pricing and includes interaction terms to investigate the combined effects of predictors.


## Model Diagnostics
Diagnostics are performed to check the validity of the model assumptions, identify potential outliers, and understand the impact of influential points.



## Results
The analysis reveals how various factors such as distance from employment centers and number of rooms significantly influence the housing prices in Boston. Detailed statistical outputs are provided to support the conclusions.

## Conclusion
This project demonstrates the power of linear regression in real estate economics, providing insights into factors that affect housing prices in urban areas. The models and diagnostics used herein lay a foundation for further research and more complex analyses, such as machine learning applications in housing price prediction.


## Authors
Krystal Lin

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

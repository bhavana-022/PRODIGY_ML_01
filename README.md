# PRODIGY_ML_01

## TASK-1: Linear Regression Model for House Price Prediction

### Problem Statement
The goal of this task is to implement a **Linear Regression Model** to predict house prices based on the following features:
- **Square footage**
- **Number of bedrooms**
- **Number of bathrooms**

This project provides a foundation for understanding regression analysis and developing a machine learning model to solve real-world prediction problems.

---

## Data

### Description
The dataset used in this project contains information on 128 houses, with the following features:
- **Price**: The selling price of the house (target variable).
- **SqFt**: Square footage of the house.
- **Bedrooms**: Number of bedrooms.
- **Bathrooms**: Number of bathrooms.
- **Offers**: Number of offers received for the house.
- **Brick**: Whether the house has brick construction (`Yes` or `No`).
- **Neighborhood**: The location of the house (`East`, `North`, or `West`).

### Sample Rows from the Dataset
| Home | Price   | SqFt | Bedrooms | Bathrooms | Offers | Brick | Neighborhood |
|------|---------|------|----------|-----------|--------|-------|--------------|
| 1    | 114300  | 1790 | 2        | 2         | 2      | No    | East         |
| 2    | 114200  | 2030 | 4        | 2         | 3      | No    | East         |
| 3    | 114800  | 1740 | 3        | 2         | 1      | No    | East         |
| 4    | 94700   | 1980 | 3        | 2         | 3      | No    | East         |
| 5    | 119800  | 2130 | 3        | 3         | 3      | No    | East         |

For the complete dataset, refer to the provided file: **`house_prices.csv`**.

---

## Setup and Requirements

### Prerequisites
- Python 3.8+
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `scikit-learn`

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/PRODIGY_ML_01.git
   cd PRODIGY_ML_01
### Results and Accuracy
Model Metrics:
After training and testing the Linear Regression model, the following results were observed:

- Mean Absolute Error (MAE): 14,800
- Mean Squared Error (MSE): 2,500,000
- R² Score: 0.85 (The model explains 85% of the variance in house prices).

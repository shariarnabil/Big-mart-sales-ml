# Big Mart Sales Prediction: A Machine Learning Approach to Forecast Sales Across 10+ Store Categories

This project aims to predict the sales of various Big Mart stores using historical sales data. The prediction model leverages machine learning algorithms to assist Big Mart in optimizing store operations and inventory management by forecasting future sales. The project focuses on improving model accuracy through advanced data preprocessing, feature engineering, and algorithm selection.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Dataset](#dataset)
- [Modeling Approach](#modeling-approach)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Contributing](#contributing)


## Project Overview

This project involves building machine learning models to predict the sales for Big Mart stores based on multiple factors such as store size, location, and product attributes. We explored various regression models, including **Linear Regression**, **XGBoost**, and **Decision Tree Regressor**, to create a reliable prediction system.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/shariarnabil/Big-Mart-Sales-Prediction.git
   cd Big-Mart-Sales-Prediction
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Dataset

The dataset used in this project is provided by [Big Mart Sales]). It contains historical sales data, including information about:

- **Item Identifier**
- **Item Weight**
- **Item Visibility**
- **Item Type**
- **Item MRP**
- **Outlet Identifier**
- **Outlet Establishment Year**
- **Outlet Size**

## Modeling Approach

The following steps were taken to develop the prediction model:

1. **Data Cleaning and Preprocessing**:
   - Handled missing values and performed outlier detection.
   - Standardized and encoded categorical variables.
   - Performed feature scaling for numerical variables.

2. **Feature Engineering**:
   - Created new features like `Item_Visibility_Squared`, and `Years_Established` to improve model accuracy.
   - Used feature selection techniques to identify the most relevant variables.

3. **Model Selection**:
   - Built models using **Linear Regression**, **Random Forest**, and **XGBoost**.
   - Evaluated model performance using metrics like **Mean Squared Error (MSE)** and **R-squared**.

## Results

- **Linear Regression**: Achieved an MSE of 1500 and an R-squared of 0.65.
- **XGBoost**: Outperformed other models with an MSE of 1200 and an R-squared of 0.72.
- **Decision Tree Regressor**: Delivered moderate performance with an MSE of 1300 and an R-squared of 0.68.

The **XGBoost** model provided the best sales prediction accuracy, making it the final choice for deployment.

## Technologies Used

- **Python**
- **Jupyter Notebooks**
- **pandas**, **NumPy** for data manipulation
- **scikit-learn** for building machine learning models
- **XGBoost** for boosting model accuracy
- **Matplotlib**, **Seaborn** for data visualization

## Usage

1. Load the dataset into the notebook.
2. Run the preprocessing steps to clean and transform the data.
3. Train the model using the provided algorithms.
4. Evaluate the model performance on the test dataset.

```bash
python train_model.py
```

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any improvements or bug fixes.





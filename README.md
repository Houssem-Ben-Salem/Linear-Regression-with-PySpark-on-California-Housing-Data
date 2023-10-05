# Linear-Regression-with-PySpark-on-California-Housing-Data

### Project Overview

This project implements a Linear Regression model using PySpark's Machine Learning library to predict housing values in Californian districts, given a number of features from these districts. The dataset used for this project is based on data from the 1990 California census.

### Dependencies

- Python 3
- PySpark
- Seaborn
- Matplotlib
- Pandas
- NumPy

### Data Exploration

Before diving into the machine learning model, the dataset underwent exploration and preprocessing:

1. **Load Data**: The data is loaded directly from the repository.
2. **Data Exploration**: 
   - Distribution of the median age of the people living in the area.
   - Summary statistics to understand the data distribution.
3. **Data Preprocessing**:
   - The target variable, median house value (`medhv`), is adjusted.
   - Feature engineering is performed to derive meaningful insights such as rooms per household, population per household, and bedrooms per room.
   - Features are assembled into a single vector and then standardized.
   
### Linear Regression Model

1. The dataset is split into training and test sets.
2. An ElasticNet linear regression model is defined and trained using the training dataset.
3. The trained model's performance is evaluated using metrics like RMSE and R².

### Evaluation

Various metrics such as RMSE (Root Mean Squared Error), MAE (Mean Absolute Error), and R² (coefficient of determination) are used to evaluate the model's performance.

### How to Run

1. Ensure you have all the required dependencies installed.
2. Clone the repository.
3. Load the dataset directly from the repository's root or data folder.
4. Run the provided Jupyter notebook.

### Contributing

Contributions are welcome! Please feel free to submit a pull request or raise any issues.

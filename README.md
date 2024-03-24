# <span style="color:#006400">Simple Linear Regression</span>

This project demonstrates the implementation of Simple Linear Regression using the scikit-learn library in Python. The goal is to <span style="color:#8B008B">predict the salary of employees based on their years of experience</span>.

## <span style="color:#800000">Dataset</span>

The dataset used in this project is `Salary_Data.csv`, which contains two columns:

- `YearsExperience`: The number of years of experience for an employee.
- `Salary`: The corresponding salary for the employee.

![Dataset Sample](images/dataset_sample.png "Sample of the dataset")

## <span style="color:#000080">Results</span>

The script will display two plots:

1. **Salary vs. Experience (Training set)**: This plot shows the scatter plot of the training data points and the regression line fitted to the training data.

   ![Training Set Plot](images/training_set_plot.png "Salary vs. Experience (Training set)")

2. **Salary vs. Experience (Test set)**: This plot shows the scatter plot of the testing data points and the regression line fitted to the training data.

   ![Test Set Plot](images/test_set_plot.png "Salary vs. Experience (Test set)")

## <span style="color:#008000">Dependencies</span>

The following Python libraries are required to run this project:

- NumPy
- Matplotlib
- Pandas
- Scikit-learn

You can install these libraries using pip:

## <span style="color:#800080">Usage</span>

1. Clone this repository or download the source code.
2. Make sure you have the `Salary_Data.csv` file in the same directory as the Python script.
3. Run the Python script:

The script will perform the following steps:

1. Import the required libraries.
2. Load the dataset from `Salary_Data.csv`.
3. Split the dataset into training and testing sets.
4. Train a Simple Linear Regression model on the training set.
5. Make predictions on the testing set.
6. Visualize the training set results by plotting a scatter plot and the regression line.
7. Visualize the testing set results by plotting a scatter plot and the regression line.

## <span style="color:#008B8B">Contributing</span>

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.


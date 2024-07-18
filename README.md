# User Defined Linear_Reg for Head-Brain Case Study


Here's a `README.md` file description for your GitHub repository:

---

# Head and Brain Size Linear Regression

## Introduction

This project demonstrates the application of linear regression on a dataset containing head and brain size measurements. The goal is to predict brain weight based on head size using the Least Squares Method.

## Dataset

The dataset used in this project is `HeadBrain.csv`, which contains the following columns:
- `Head Size(cm^3)`
- `Brain Weight(grams)`
- Additional columns not used in this analysis

## Implementation

### Steps:
1. **Data Loading**:
    - The dataset is loaded using pandas.
    - The size of the dataset is printed.

2. **Data Preparation**:
    - Extract `Head Size(cm^3)` as feature `X`.
    - Extract `Brain Weight(grams)` as target `Y`.

3. **Linear Regression**:
    - Compute the mean of `X` and `Y`.
    - Calculate the slope (`m`) and y-intercept (`c`) of the regression line using the Least Squares Method.
    - Print the slope and y-intercept.

4. **Visualization**:
    - Plot the regression line along with the scatter plot of the original data points using matplotlib.

5. **Goodness of Fit**:
    - Calculate the R-squared value to evaluate the fit of the regression model.
    - Print the R-squared value.



### Output:
```
___Vaishnavi_Talekar___
__Supervised_Machine_Learning__
Linear Regression on Head and Brain size data set
Size of DataSet  (237, 4)
Slope of Regression line is  0.027353483707844323
Y intercept of Regression line is  1183.471088758299
0.1258742903771135
```

![image](https://github.com/user-attachments/assets/4897eb45-2f6c-457b-9172-a5d2be2ba0ac)


## Requirements

- numpy
- pandas
- matplotlib

## How to Run

1. Clone the repository:
    ```
    git clone https://github.com/Vaishnavit08/HeadBrainPredictor.git
    ```
2. Navigate to the project directory:
    ```
    cd HeadBrainPredictor
    ```
3. Ensure you have the required libraries installed. You can install them using:
    ```
    pip install numpy pandas matplotlib
    ```
4. Run the script:
    ```
    python script_name.py
    ```

## Conclusion

This project illustrates a simple implementation of linear regression to understand the relationship between head size and brain weight. The computed R-squared value indicates the goodness of fit of the model.

## Author

- Vaishnavi Talekar

---



# Sonar Data Classification

This project demonstrates a simple classification model using Logistic Regression to distinguish between rocks and mines based on sonar data.

## Dataset

The dataset used in this project is the Sonar dataset, which contains 60 numerical attributes representing the sonar signals and a target variable indicating whether the object is a rock ('R') or a mine ('M').

## Project Structure

The project is implemented in a Python notebook and includes the following steps:

1.  **Data Loading and Preprocessing**: Loading the dataset into a pandas DataFrame, exploring its shape and descriptive statistics, and separating the features (X) from the target variable (Y).
2.  **Data Splitting**: Splitting the data into training and testing sets using `train_test_split` with stratification to maintain the class distribution.
3.  **Model Training**: Training a Logistic Regression model on the training data.
4.  **Model Evaluation**: Evaluating the performance of the trained model on both the training and testing data using accuracy score.
5.  **Predictive System**: Implementing a function to make predictions on new input data.

## How to Run

1.  Clone the repository.
2.  Ensure you have the necessary libraries installed (pandas, numpy, scikit-learn).
3.  Open and run the Python notebook.

## Dependencies

-   pandas
-   numpy
-   scikit-learn

## Results

The model achieves an accuracy of approximately 78 % on the training data and 75 % on the test data.

## Future Improvements

-   Experiment with other classification algorithms (e.g., Support Vector Machines, Random Forests).
-   Perform hyperparameter tuning to optimize model performance.
-   Increase train and test datacases

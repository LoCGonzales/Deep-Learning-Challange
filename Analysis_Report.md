#  Neural Network Model Report

## Overview of the Analysis
### Purpose:
The goal of this project is to create a machine learning model that predicts whether funding applicants will succeed, helping Alphabet Soup make better decisions about who to fund.

## Results
### Data Preprocessing
### Target Variable:
The target variable is IS_SUCCESSFUL, which shows whether funding was used effectively.

### Feature Variables:
Features include APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT.

### Removed Variables:
The columns EIN and NAME were removed because they are just IDs and don’t help with predictions.

## Compiling, Training, and Evaluating the Model
### Model Architecture:

### The model has two hidden layers:
First hidden layer: 80 neurons, ReLU activation.
Second hidden layer: 30 neurons, ReLU activation.
The output layer uses a sigmoid activation for binary classification.

### Performance:
The optimized model achieved:

Accuracy: 76.8%
Loss: 0.55
This means the model works well and exceeds the target accuracy of 75%.

## Optimization Steps:
### To improve accuracy, the following changes were tested:
Changing the number of neurons in each layer.
Adding or removing layers.
Trying different activation functions.
Adjusting the number of training epochs.

## Summary
### Overall Results:
The final model achieved an accuracy of 76.8%, showing that it can reliably predict the success of funding applicants.

### Recommendations:
Other methods, like Random Forests or Gradient Boosting Machines, could be explored in the future. These might perform even better because they handle complex feature interactions differently.

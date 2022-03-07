# Neural Network Model - Charity Analysis

## Project Overview

## Results

### Data Preprocessing
- ***Target variables***: The target variable is the `IS_SUCCESSFUL` column, indicating whether or not the money was used effectively.
- ***Features***: The features were all the columns except the target column, and the ID columns (`EIN` and `NAME`)
- ***Removeable variables***: The variables that were removed were the `EIN` and `NAME` columns- since these columns are simply identifiers and do not contribute to whether the money was used effectively.

### Compiling, Training, and Evaluating the Model
#### ***Neurons, layers, and activation functions***
The parameters for the neural network model structure were initially chosen to match the output from the starter code- this seemed like a decent starting point for the model.

- input layer:
    - set to `len(X_train_scaled[0])` to match number of features in the model
- hidden layer 1:
    -  `units` = 80
    - activation = `relu`
- hidden layer 2:
    - `units` = 30
    - activation = `relu`
- output layer:
    - `units` = 1
    - activation = `sigmoid`

***Was target model performance achieved?***<br>
The model accuracy was initially 72.6%, which is just short of the 75% cutoff. This indicated that some optimization would be needed to reach the goal accuracy.<br>

***Steps taken to optimize model***<br>


## Summary
- Overall results
- recommendation for how a different model could solve this classification problem
## Overview of the Analysis

The purpose of this project was to create a tool for the nonprofit foundation, Alphabet Soup, that can assist in selecting the applicants for funding with the best chance of success in their ventures.

## Results

### Data Preprocessing
- What variable(s) are the target(s) for your model?
    - The target variable for this dataset was the IS_SUCCESSFUL column.
- What variable(s) are the features for your model?
    - The following variables are the features for our model:
      * NAME
      * APPLICATION_TYPE
      * AFFILIATION
      * CLASSIFICATION
      * USE_CASE
      * ORGANIZATION
      * STATUS
      * INCOME_AMT
      * SPECIAL_CONSIDERATIONS
      * ASK_AMT
- What variable(s) should be removed from the input data because they are neither targets nor features?
    - The variables NAME and EIN were removed from the input data.

### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - Number of Neurons:
        * First Hidden Layer: 8 neurons
        * Second Hidden Layer: 5 neurons
        * Output Layer: 1 neuron
    - Number of Layers:
        * The model has three layers: one input layer, two hidden layers, and one output layer.
    - Activation Functions:
        *


## Summary

* The model achieved an accuracy of 73.88%, indicating that it correctly predicted the class of the data points nearly 74% of the time.
* The loss value of 0.5224 suggests that the model's performance in terms of minimizing errors during training was moderate.
* Since the accuracy is around 73.88%, there is room for improvement. Hyperparameter tuning may improve the model's performance. Techniques like adjusting learning rates, trying different optimizers, or modifying the network architecture could help enhance the model's accuracy.

# Neural Network Charity Analysis

## Overview:
With the knowledge of machine learning and neural networks, we used the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results
### Data Preprocessing
#### 1. What variable(s) are considered the target(s) for your model?
We need to check if the target is marked as successful in the DataFrame, indicating that it has been successfully funded by AlphabetSoup.

#### 2. What variable(s) are considered to be the features for your model?
The IS_SUCCESSFUL column is the feature for this model.

#### 3.What variable(s) are neither targets nor features, and should be removed from the input data?
We dropped column EIN and NAME as they are not increasing the accuracy of the results.

### Compiling, Training, and Evaluating the Model

#### 4. How many neurons, layers, and activation functions did you select for your neural network model, and why?

In the optimized model, layer 1 started with 100 neurons with a sigmoid activation. For layer 2, it dropped to 80 neurons and continued with the sigmoid activation. For layer 3, we applied 40 neurons with relu activation and layer 4 has 20 neurons and continued with relu activation.

#### 5. Were you able to achieve the target model performance?
No. Unfortunately the target is to reach 75% but the best result I had was 72.36%

#### 6. What steps did you take to try and increase model performance?
I tried by adding layers, changing the activation type and number of neurons in each layer.

## Summary
I had a accuracy result of 72.36% not eaching 75% target. There could be several reasons for this result, for example, we are not adding enough layers or choosing the correct activation type.

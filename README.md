# Neural_Network_Charity_Analysis
## Overview
The purpose of this module is to create a binary classifier that is capable of predicting if applicants will be successful if they are bunded by Alphabet Soup.

## Results
Data Preprocessing
- What variable(s) are considered the target(s) for your model?
  - The variable we selected was the IS_SUCCESSFUL column.
- What variable(s) are considered to be the features for your model?
  - all of the columns besides IS_SUCCESSFUL.
- What variable(s) are neither targets nor features, and should be removed from the input data?
  - We dropped EIN and NAME
Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - We selected 2 layers, 80 and 30 neurons respectively.
- Were you able to achieve the target model performance?
  - We were not able to hit the 75% accuracy mark.
- What steps did you take to try and increase model performance?
  - I tried decreasing the 2nd hidden layer bin size, and added a third hidden layer with varying sizes.
 
## Summary
It may be worth looking into a supervised machine learning model. 

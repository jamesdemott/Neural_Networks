# Neural_Networks

## Overview
The purpose of this exercise was to build a binary classifier that is capable of predicting whether an applicant is likely to be successful in order to inform where investments ought to be made. 


## Results
### Data Preprocessing
What variable(s) are considered the target(s) for your model?
* Our independent variables or features are the columns: 'APPLICATION_TYPE',
 'AFFILIATION',
 'CLASSIFICATION',
 'USE_CASE',
 'ORGANIZATION',
 'INCOME_AMT',
 'SPECIAL_CONSIDERATIONS'
 * Our dependent variable is 'IS_SUCCESSFUL' 
 
What variable(s) are neither targets nor features, and should be removed from the input data?
* Columns that are neither features nore targets that I removed are 'EIN', and 'NAME'. 

### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?

First Attempt: 
* 2 layers; Layer One = 10 neurons, Layer 2 = 20 neurons

![First Attempt Screenshot] (

Second Attempt: 
* 2 layers; Layer one = 60 neurons, Layer 2 = 25 neurons
![Second Attemtp Screenshot] (


Were you able to achieve the target model performance?



What steps did you take to try and increase model performance?


## Summary
There is a summary of the results (2 pt)
There is a recommendation on using a different model to solve the classification problem, and justification (3 pt)

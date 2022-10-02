# Neural_Network_Charity_Analysis
## Overview
Using data received from Alphabet Soup, we are tasked with developing a deep learning model that can correctly identify which organizations that request funding will be successful. 
## Results
### Important Questions to Answers
#### Data PreProcessing
- What variable(s) are considered the target(s) for your model?
  - The most important variable for this data set is to find out if the project was successful. All of the other variables could potentially factor into whether a project was successful, which is why we developed a neural network to see if we could accurately predict the outcomes with the data on hand. 
- What variable(s) are considered to be the features for your model?
  - All other columns in the data set would be considered features, if we did not drop them. The two we dropped EIN and NAME were not important when looking at the data so they would not be considered features.
- What variable(s) are neither targets nor features, and should be removed from the input data?
  - The two variables that are neither targets nor features would be EIN and NAME.
#### Compiling, Training, and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - I selected 3 layers, input hidden and output. RELU was chosen as the activation function as it only gives positive outputs, is easier to train, and oftentimes achieves better performance. 
- Were you able to achieve the target model performance?
  - Unfortunately, I was not able to achieve the target model performance when attempting to optimize the deep learning model that was being used. 
- What steps did you take to try and increase model performance?
  - In an attempt to increase model performance I: 
    - Added an additional hidden layer with 5 neurons. 
    - Attempted to remove extraneaous features. 
    - Altered the # of neurons in the existing layers. 
## Summary
Overall, prior to my attempt at optimization, we were able to achieve roughly 72% accuracy regarding predicting whether a campaign is successful or not after they receive funding. I believe that 75% for this particular application, is an acceptable level of accuracy as there will always be some inherent risk when providing funding for external institutions. 
### Suggestion
A suggestion would be to potentially look at implementing a classification model since the only outcomes we're interested in are "Successful" and "Not Successful". 

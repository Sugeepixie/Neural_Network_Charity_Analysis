# Neural_Network_Charity_Analysis
## Overview
The purpose of this was to develop a neural network to determine which organization should be considered for funding from AlphabetSoupCharity.

## Results
* Data Preprocessing
1. What variable(s) are considered the target(s) for your model?
   IS_SUCCESSFUL coulumn is the target of the model.

   ![Target](https://user-images.githubusercontent.com/76926148/210296624-60892cc5-1cb1-45e3-a65a-e943c7705030.PNG)

2. What variable(s) are considered to be the features for your model?
   APPLICATION_TYPE, ASK_AMT, INCOME_AMT, CLASSIFICATION, AFFILIATION, SPECIAL_CONSIDERATIONS, STATUS, USE_CASE

   ![Features](https://user-images.githubusercontent.com/76926148/210296653-5b3d061f-4e73-4026-abdb-93192fc26490.PNG)




3. What variable(s) are neither targets nor features, and should be removed from the input data?
   EIN, NAME

   ![Drops](https://user-images.githubusercontent.com/76926148/210296680-9ddc6e88-ec52-4e9f-85f3-3ee3a1592671.PNG)


* Compiling, Training, and Evaluating the Model
1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
   In the first attempt, the model was set with 2 layers of 80 and 30 neurons and "relu" as the activation feature.


2. Were you able to achieve the target model performance?
  The accuracy was designed to be lower than 75%. The overall accuracy achieved was 72.5% but reached to 74.1% at epochs of 100.


3. What steps did you take to try and increase model performance?
   To improve performance 3 attempts were made with changes mentioned below.
   Removed SPECIAL_CONSIDERATIONS column, increased nuerons and hidden layers, changed output activation layer to tanh, and increased epochs to 200

## Summary
The Initial setup of this model and optimizations did not improve performance at the requred level so my reccommendation would be to use supervised machine learning model like Random Forest Classifier.



# Neural_Network_Charity_Analysis

## OverView of the Analysis


Using Machine Learning and Neural Networks for this project, I used the features in the dataset to 
create a binary classifier that will help to predict if the applicants that will be funded by a Charitable
organization called Alphabet Soup will be successful. For this analysis we had a dataset containing various 
measures on 34,000 organizations that have been funded by Alphabet Soup. This project compromised of the 
following 3 steps:

  . Preprocessing the data for the neural network
  . Compile, Train and Evaluate the Model
  . Optimizing the model

## Results

## Data Processing

    .Variable that was considered as the target for my model: IS_SUCCESSFUL Column
    .Variables that were considered features for my model: Every Column except for IS_SUCCESSFUL 
     which is our target and the ones we will drop
    .Variable that were neither targets or features for the dataset: 
     Columns that I dropeed are EIN, NAME because they will have little to no impact om our outcome


## Compiling, Training and Evaluating the Model

The number of neurons, layers, and activation functions that i use for my neurons network model are as follow:

  . For my neuronal network model had 2 hidden layers. The first layer had 80 neurons, and the second has 30,
    there is also an output layer. The first and second layers have the reul activation function and the activtion
    function for the output layer is sigmoid.
    
Was the model able to achieve the target model performance?
  
  . The model was not able to reach the target 75%. The accuracy for the model was 68%.
  
  
Steps taken to try and increase model performance
  . step 1: Remove addiditonal feature that is the USE_CASE olumn.
  
  
  
  . Step 2: Added additional neurons to the hidden layers. As a result of the added layer, the accuracy score 
          ``went down, this time to 50%.

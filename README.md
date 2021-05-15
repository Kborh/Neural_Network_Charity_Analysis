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
     which is the target and the ones we will drop
    .Variable that were neither targets or features for the dataset: 
     Columns that I dropeed are EIN, NAME because they will have little to no impact om our outcome


## Compiling, Training and Evaluating the Model

The number of neurons, layers, and activation functions that i use for my neurons network model are as follow:

  . For my neuronal network model had 2 hidden layers. The first layer had 80 neurons, and the second has 30,
    there is also an output layer. The first and second layers have the reul activation function and the activtion
    function for the output layer is sigmoid as illustrated by the image in the images foldere.
    
Was the model able to achieve the target model performance?
  
  . The model was not able to reach the target 75%. The accuracy for the model was 73% as shown in the images folder.
  
  
Steps taken to try and increase model performance
  . step 1: Removed addiditonal feature that is the STATUS column.
  
  
  
  . Step 2: Added additional neurons to the hidden layers to the network model. 
     I also changed the values of the layers to see if there would be a n imporovement in the accuracy score.
     An image of the added feature can be found in the images folder.
     
     The Accuracy score didn't reached 75% after the added neuron, there wasn't any changed to the accuracy score 73%. 
     An image of the day outcome is in the images folder.
     
 . Step 3: I changed the activation function of the output layer to 'tanh', but that didn't changed the accuracy sroce.
    the accuracy score stayed at 73%. Images of these results can be found in the images folder.
    
    
## Summery
      The model ended up with the accuracy score of 73%% after optimization. The initial neural network had an accuracy 
      score of 73% as well. There was no increase or decrease in accuracy score after optimization. But we could further optimize 
      our neural network by removing more features or simply adding more data to the dataset to increase accuracy. Since our accuracy 
      score was not particularly up to the standard with neural networks, we could have used the Random Forest classifiers. This is 
      because random forest is a robust and accurate model due to their sufficient number of estimators and tree depth. Also the
      random forest models have a faster performance than neural networks and could have avoided the data from being overfitted.

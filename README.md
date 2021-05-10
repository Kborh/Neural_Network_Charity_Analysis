# Neural_Network_Charity_Analysis

## OverView of the Analysis


Using Machine Learning and Neural Networks for this project, I used the features in the dataset to 
create a binary classifier that will help to predict if the applicants that will be funded by a Charitable
organization called Alphabet Soup will be successful. For this analysis we had a dataset containing various 
measures on 34,000 organizations that have been funded by Alphabet Soup. This project compromised of the 
following 3 steps:

  .Preprocessing the data for the neural network
  .Compile, Train and Evaluate the Model
  .Optimizing the model

## Results

## Data Processing

    .Variable that was considered as the target for my model: IS_SUCCESSFUL Column
    .Variables that were considered features for my model: Every Column except for IS_SUCCESSFUL 
     which is our target and the ones we will drop
    .Variable that were neither targets or features for the dataset: 
     Columns that I dropeed are EIN, NAME because they will have little to no impact om our outcome

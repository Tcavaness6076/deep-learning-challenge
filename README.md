# Deep-Learning-Challenge
## Table of Contenets
* [Overview](#Overview)
* [Results](#Results)
* [Summary](#Summary)
## Overview
In this analysis we used features witin our data set to create binary classifers that were then used to predict of whether or not applicants would be successful in obtaining funding from Alphabet Soup. 
The dataset provided contained over 34,000 organizations that have received funding from Alphabet Soup. We cleaned up the data removing the categories 'EIN' and 'Name' since we are mainly using the data
to predict the likelihood of obtaining funding. Next we compiled the data, trained the data and evaluated our model. Finally we worked to optimize the model.
## Results
* Model:
  * Hidden Layer 1: Type = Dense, Output = None, Shape = 9, Param # = 414
  * Hidden Layer 2: Type = Dense, Output = None, Shape = 10, Param # = 100
  * Output Layer:  Type = Dense, Output = None, Shape = 1, Param # = 11
  * Total Params: 525
  * Trainable Params: 525
  * Non-trainable Params: 0
* Model Results:
  * Loss: 0.55
  * Accuracy: 0.72
## Summary
We acheived an accuracy of 72% with our test data but had a loss of 55% with the same data. 

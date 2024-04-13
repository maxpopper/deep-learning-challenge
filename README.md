# deep-learning-challenge

All code is located in `Starter_Code.ipynb`

Please see below for my analysis report

# Analysis Report

## Overview
The purpose of this analysis is to evaluate all applicants and determine which will be the most successful if granted funding by Alphabet Soup.

## Results
### Data Preprocessing
* The target variable for the model is *'IS-SUCCESSFUL'*.
* The feature variables for the model are *'APPLICATION_TYPE'*, *'AFFILIATION'*, *'CLASSIFICATION'*, *'USE_CASE'*, *'ORGANIZATION'*, *'STATUS'*, *'INCOME_AMT'*, *'SPECIAL_CONSIDERATIONS'*, and *'ASK_AMT'*.
* The variables that should be removed before fitting the model are *'EIN'* and *'NAME'*.

### Compiling, Training, and Evaluating the Model
* I chose to use 2 hidden layers. The first layer has 85 neurons and the second layer has 45 neurons. I used *ReLU* as the activation function for my hidden layers and *Sigmoid* for the output layer.
* Ultimately, I was not able to achieve the target model performance. I maxxed out at ~72.4% accuracy.
* I played around with the number of layers in the model. I als tried adding neurons to each layer in hopes of improving accuracy, but ultimately these efforts failed to get the model to the target accuracy benchmark.

## Summary
The deep learning model proved to be somewhat accurate in predicting an organization's success if funded. Ultimately, to improve the model's accuracy, I would recommend using a different deep learning model, such as a convolutional neural network.
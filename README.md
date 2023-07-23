# Deep Learning Challenge

## Overview:
The goal was to create a binary classifier to predict whether applicants will be successful if funded by Alphabet Soup.  A large data set was provided and included the following: 
  * EIN and NAME—Identification columns
  * APPLICATION_TYPE—Alphabet Soup application type.
  * AFFILIATION—Affiliated sector of industry.
  * CLASSIFICATION—Government organization classification
  * USE_CASE—Use case for funding
  * ORGANIZATION—Organization type
  * STATUS—Active status
  * INCOME_AMT—Income classification
  * SPECIAL_CONSIDERATIONS—Special considerations for application
  * ASK_AMT—Funding amount requested
  * IS_SUCCESSFUL—Was the money used effectively

## Results: Using bulleted lists and images to support your answers, address the following questions:

### Data Preprocessing

* The target variable for this model was the "IS_SUCCESFUL" COLUMN
* All the other data was used as the features for the model
* The 2 ideentification columns "EIN" and "NAME" were removed
* Data was cleaned, binned, and scaled, which resulted in 43 features for splitting and training

### Compiling, Training, and Evaluating the Model
* The highest model performance achieved was 72%.
    * Model 1 parameters:
      - neurons = 80, 30
      - hidden layers = 2
      - activation = ReLu
    * Model 2 parameters:
      - neurons = 16, 16
      - hidden layers = 2
      - activation = ReLu
    * Model 3 parameters:
      - neurons = 80, 30
      - hidden layers = 2
      - activation = Tanh
    * Model 4 parameters:
      - neurons  = 46, 26, 10, 60
      - hidden layers = 4
      - activation = ReLu

### Summary: 
  * Failed to achieve target accuracy of 75%
  * Data classification needs to be improved. Future attempts should use a variety of classification methods

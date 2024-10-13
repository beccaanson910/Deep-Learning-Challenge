# Deep-Learning-Challenge

# Overview

The objective of this challenge was to use Machine Learning to analyze the funding data from Alphabet Soup and create an application that will be able to select the most optimal applicants for the company to fund.


# Results

The "IS_Successful" column is the target of the model
The features of the model are: Application Type, Affiliation, Classification, Use Case, Organization, Status, Income Amount, Special Considerations, and Ask Amount
The variables that were dropped from the dataset: "EIN", "NAME"


# Compiling, Training, & Evaluating the model
- Attempt #1: 
    - Hidden Layer Units: 16, 16, 1
    - Activations: Relu, Relu, Sigmoid (Output)
    - Epochs: 100
    - Accuracy: 72.38%

- Attempt #2
    - Hidden Layer Units: 50, 20, 1
    - Activations: Relu, Relu, Sigmoid (Output)
    - Epochs: 100
    - Accuracy: 72.50%

- Attempt #3
    - Hidden Layer Units: 5, 2, 1
    - Activations: Relu, Relu, Sigmoid (Output)
    - Epochs: 100
    - Accuracy: 72.45%

- Attempt #4
    -Hidden Layer Units: 100, 40, 1
    - Activations: Relu, Relu, Sigmoid (Output)
    - Epochs: 100
    - Accuracy: 72.52%


# How many neurons, layers, and activation functions did you select for your neural network model, and why?
The above parameters were used for the following reasons:
    - Increasing the number of neurons could increase the model's performance
    - Adding more than one layer could also help with the model's performance


# Were you able to achieve the target model performance?
Unfortunately I was unable to achieve the target model performance of 75%. The highest accuracy that I was able to achieve was 72.52%.


# What steps did you take in your attempts to increase model performance?
On each attempt, the number of neurons were changed for both layers to increase the model's performance.


# Summary
The fourth Optimization attempt yielded the best accuracy for the model whicn is 72.52%. Even though the target performance was not achieved, the accuracy with the different attempts did not fall below 72%, which is reassuring.
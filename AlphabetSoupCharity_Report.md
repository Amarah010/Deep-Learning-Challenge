# Report on the Neural Network Model

## Overview of the analysis

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. 

Alphabet Soup’s business team provided a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.

The purpose of this analysis, With the knowledge of machine learning and neural networks, is to use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

## Results

### Data Preprocessing:
- Target Variables for the Model: IS_SUCCESSFUL.
- Feature Variables for the Model: APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.
- Variables removed from the input data because they are neither targets nor feature: EIN, NAME.

### Compiling, Training, and Evaluating the Model:

- Model 1: I used 2 hidden layers, with 10 neurons for both and epochs 100. The result was 71%.
- Model 2: I used 3 hidden layers, with 8, 8 and 5 neurons and epochs 50. The result was 71%.
- Model 3: I added the NAME column back in and used 2 hidden layers with 5 neurons each and epochs 50. The result was 70%.

Steps taken to increase model performance:
- Added more layers and columns as well as experimenting with the number of nodes and neurons.

## Summary

Overall, the neural network model was unsuccessful as it reached only a maximum of 71% accuracy.
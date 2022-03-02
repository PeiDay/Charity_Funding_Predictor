# Charity_Funding_Predictor

## Background

The non-profit foundation Alphabet Soup wants to create an algorithm to predict whether or not applicants for funding will be successful. To Create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup, based on a dataset containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.

System Requirement: Python 3.7

## Preprocess the data
* Cleaned data, and for columns with more than 10 unique values.
* Determined the number of data points for each unique value.
* Scikit-Learn’s `StandardScaler()` to preprocess the dataset. 
* Selected a cutoff point to bin "rare" categorical variables together in a new value.
* `pd.get_dummies()` is used to do one-hot encode categorical variables.

## Compile, Train, and Evaluate the Model
Designed a neural network to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on features in this dataset.

* Created a neural network model by assigning the number of input features and nodes for each layer using Tensorflow Keras.
* Created the hidden layers and chose appropriate activation function.
* Created an output layer with an appropriate activation function.
* Compiled and trained the model.
* Created a callback that saves the model's weights every 5 epochs.
* Evaluated the model using the test data to determine the loss and accuracy.
* Saved and exported your results to an HDF5 file, and name it `AlphabetSoupCharity.h5`.


## Optimize the Model
* Optimized model in order to achieve a target predictive accuracy higher than 75%.

## Results
* First attempt wasn't be able to achieve the target performance 75; the accuracy rate was 72%. 

* Following attempt: after higher the test size, adding another layer, change the activation, still weren't be able to achieve the target 75%.  The loss value of 55 implies that the model could be further optimized. The accuracy value of the models show that 72-74% of the model's predicted values align with the true values in the original dataset.